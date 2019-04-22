# Welcome to the gov2formfield wiki!
## Tag
```
<gov2formfield :action=""></gov2formfield>
```
## Property
- fieldUrl: **type: String** //
- action: **type: String** //
- show: **type: Boolean** //
- parent_id: **type: Number** //
## Data
 - isConfirm: false
 - isOpen: false
 - submit: 'Add'
 - fields: []
 - delData: ''
 - isDel: true
 - isHasChildren: false
 - isDisabled: []
 - form: new Form(this.fields)
 - scrollOptions: {
     easing: 'ease-in',
     x: false,
     y: true
   },
 - selected: []
 ## Methods
 - resetButton //
 - scrollTo //
 - toggleForm //
 - onSubmit //
 - responseBox //
 - refreshBrowser //
 - formSuccess //
 - formFail //
 - formEdit //
 - formConfirmDel //
 - formConfirmHasChildren //
 - delProceed //
 - confirmClose //
 - setFields //
 - setParentId //
 - setLevel //
 - listenComponent //
 - setField //
 ## Created
 - toggleForm //
 - formEdit //
 - formConfirmDel //
 - formConfirmHasChildren //
 - fieldUrl //
 - setParentId //
 - setLevel //
 - toggleForm //
