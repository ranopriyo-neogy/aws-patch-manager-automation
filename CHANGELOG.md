# Change History

## 1.0.3 (2025-04-11)

- Updated S3 bucket naming appended with random id to prevent conflict.

## 1.0.2 (2025-04-10)

- Added support for OS `Amazon Linux` and `Windows`
- Updated resource naming
- Bug Fix in `aws-pct-create-s3-stack`

## 1.0.1 (2025-04-10)

- Added `sit` environment to `aws-pct-backup-and-patch-stackset` and `aws-pct-monitoring-backup-stackset`

## 1.0.0 (2025-04-09)

- Merged Backup Role template with `aws-pct-backup-and-patch-stackset` stackset
- Update S3 bucket policy to allow just `s3:PutObject` and `s3:GetBucketAcl`.
- Updated Patch Baseline to remove `Optional` and `Extra` from patch priority.
