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
