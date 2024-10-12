<!-- BEGIN_TF_DOCS -->
# Main title

Everything in this comment block will get extracted.

You can put simple text or complete Markdown content
here.

## Requirements

The following requirements are needed by this module:

- <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) (>= 1.9)

## Providers

No providers.

## Modules

No modules.

## Resources

No resources.

## Required Inputs

No required inputs.

## Optional Inputs

The following input variables are optional (have default values):

### <a name="input_metadata"></a> [metadata](#input\_metadata)

Description: Module metadata object to give user possibility to override default module values.

Type:

```hcl
object({
    default_tags             = optional(map(string), {})
    resource_timeouts        = optional(map(map(string)), {})
    validator_error_messages = optional(map(string), {})
    validator_expressions    = optional(map(string), {})
  })
```

Default: `{}`

### <a name="input_tags"></a> [tags](#input\_tags)

Description: Key value pairs of custom tags to be applied to the module resources.

Type: `map(string)`

Default: `{}`

## Outputs

No outputs.

# Footer

Everything in this comment block will get extracted.

You can put simple text or complete Markdown content
here.
---
<sup><sub>_2024 &copy; All rights reserved - WANTED.solutions s.r.o. [<@wanted-solutions>](https://github.com/wanted-solutions)_</sub></sup>
<!-- END_TF_DOCS -->
