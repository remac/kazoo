## Menu

### About Menu

Also known as IVR. Play a prompt and branch based on caller DTMF.

#### Schema

Validator for the menu callflow data object



Key | Description | Type | Default | Required | Support Level
--- | ----------- | ---- | ------- | -------- | -------------
`id` | Menu ID to use | `string()` |   | `false` |  
`interdigit_timeout` | Amount of time, in milliseconds, to wait between keypresses | `integer()` |   | `false` |  
`skip_module` | When set to true this callflow action is skipped, advancing to the wildcard branch (if any) | `boolean()` |   | `false` |  



