Inspired from:
    Issue => https://github.com/formio/formio.js/issues/5245
    Referece file => https://github.com/formio/formio/blob/master/src/resources/Validator.js
    
Validation Test Request
http://localhost:3000/
{
    "formDefinition": {
        "components": [
            {
                "label": "Text Field",
                "applyMaskOn": "change",
                "tableView": true,
                "validate": {
                    "required": true
                },
                "key": "textField",
                "type": "textfield",
                "input": true
            },
            {
                "type": "button",
                "label": "Submit",
                "key": "submit",
                "disableOnInvalid": true,
                "input": true,
                "tableView": false
            }
        ]
    },
    "submittedData": {
        "data": {
            "textField": "1",
            "submit": false
        }
    }
}
