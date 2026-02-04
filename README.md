# oci-reporting-mock-repo
This is a repository simulating an oci-reporting repository.
## Files/
- contains `xml` and `sql` files intended for loading them into a oci database


## Manifests
- contains `yaml` manifest files per loadable file
- ASCII naming in descending order should be used to ensure the correct loading sequence

`loader_type`: describes the intended way to load the files (e.g.: `xml`, `sqlplus`, `sqlcl`)
`file_path`: relative path leading to the loadable file (e.g: `files/file.xml`)