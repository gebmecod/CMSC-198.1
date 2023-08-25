# Customizing Doctype

## Hiding a field using client script
```js
frappe.ui.form.on('School Address', { // replace School Address with target doctype
	refresh:function(frm){
		frm.toggle_display('province', false) // replace province with target field name
	}
})
```
