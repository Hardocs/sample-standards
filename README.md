In the `generate` folder you can find how the schemas were generated using yaml, then converted to json, and then generate the json schemas.
Follow the steps bellow to generate new schemas/standards.
## Workflow to generate schemas
1. Make a data object as if you would be writing metadata in yaml with this tool: https://jsonschema.net/home
   ```yaml
    type: module
    title: Basic arduino
    description: You will make sure to cover the basics of programming arduion, etc.
    isPublic: true
    isDraft: false
    level: 2
   ```
2. Then use the converted yaml into json, here is an example
   ```json
    {
        "type": "module",
        "title": "Basic arduino",
        "description": "You will make sure to cover the basics of programming arduion, etc.",
        "isPublic": true,
        "isDraft": false,
        "level": 2
    }
   ```
3. The  go to https://jsonschema.net/home and generate the sample schema with the json objec created in step 1.