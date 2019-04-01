# Operator SDK

Installs Operator SDK.

## Requirements

None

## Role Variables

| Variable        | Required | Default  | Description                                                                                                                                                                                                                                     |
| --------------- | -------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `operator_sdk_version` | :x:      | `latest` | Using `latest` will always download the latest version of the Operator SDK. You can select a specific version from [here](https://github.com/operator-framework/operator-sdk/releases). The value should match the tag. |

## Dependencies

None

## Example Playbook

```yaml
- hosts: localhost
  vars:
    atom_version: v0.6.0
  roles:
      - jaredhocutt.operator_sdk
```

