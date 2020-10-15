---
- hosts: localhost
  tasks:
  - name: Create an S3 bucket
    s3_bucket:
      name: "{{ jkg25 }}"
      region: us-east-1
      state: present
