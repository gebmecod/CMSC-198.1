## Adding a Button
```js
frappe.ui.form.on('Issue', 'refresh', function(frm) { //Issue is the doctype
	frm.add_custom_button(__("Do Something"), function() {
		alert("Hello from client script")
	});
});
```

## Change Color

### Background Color
```js
frappe.ui.form.on('Issue', {
	refresh: function(frm){
		frm.fields_dict['sb_details'].wrapper.css('background-color', 'lightblue'); // sb_details is the target field
		frm.fields_dict['section_break_19'].wrapper.css('background-color', 'gold');
	}
})
```
![[Pasted image 20230714111013.png]]
### Field Font Color and Background Color
```js
cur_frm.get_field('province').$input.css('color', 'white');
cur_frm.get_field('province').$input.css('background-color', 'black')
```
![[Pasted image 20230714111210.png]]

### Read Only
```js
cur_frm.set_df_property('customer', 'read_only', 1);
```

Ref: bit.ly/3ropQ7b