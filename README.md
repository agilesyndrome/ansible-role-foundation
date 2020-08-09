# ansible-role-foundation

## Assumptions

* Artifact Publishing:
  * Artifacts are saved to s3://bucket_name/project_name/branch_name/build_number.tar.gz
  * s3://bucket_name/project_name/branch_name/latest.txt is a text file with the latest build_number
