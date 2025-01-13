# Publish an Ansible Collection

A GitHub action to publish an Ansible collection to Galaxy (NG).

## Usage

```yaml
- name: Publish Ansible collection
  uses: syaghoubi00/action-publish-ansible-collection@v1
  with:
    galaxy-api-key: ${{ secrets.GALAXY_API_KEY }}
```

## Inputs

### `collection-path`

default: "."

description: "Path to the collection directory"

required: false

### `galaxy-api-key`

description: "API key to Ansible Galaxy"

required: true

## Outputs
