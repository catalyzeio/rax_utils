# Basic Rackspace CLI Utility Scripts
## Cloud Files
```
Usage: ./rax_cf container ls|upload|download|delete|info [file]

  container  : The name of the Cloud Files container to use

Operations:
    ls       : List the contents of the Cloud Files container
    upload   : Upload the given file to the Cloud Files container
    download : Download the given file to the Cloud Files container
    delete   : Delete the file stored in Cloud Files
    info     : Fetch the info related to the file stored in Cloud Files

Utilizes the following (read: required) environment variables:
  - RAX_USERNAME (The username for your Rackspace Cloud account)
  - RAX_APIKEY   (The API Key for your Rackspace Cloud account)
  - RAX_REGION   (The region where you want to access Cloud Files [ex: "IAD"])

Project Dependencies:
  `jq` which makes the world (or at least the terminal!) a better place: http://stedolan.github.io/jq/

Reference: http://www.rackspace.com/knowledge_center/article/cloud-files-curl-cookbook

```
