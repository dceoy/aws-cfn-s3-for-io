aws-cfn-s3-for-io
=================

AWS CloudFormation stacks of S3 buckets for I/O

[![Lint](https://github.com/dceoy/aws-cfn-s3-for-io/actions/workflows/lint.yml/badge.svg)](https://github.com/dceoy/aws-cfn-s3-for-io/actions/workflows/lint.yml)

Installation
------------

1.  Check out the repository.

    ```sh
    $ git clone git@github.com:dceoy/aws-cfn-s3-for-io.git
    $ cd aws-cfn-s3-for-io
    ```

2.  Install [Rain](https://github.com/aws-cloudformation/rain) and set `~/.aws/config` and `~/.aws/credentials`.

3.  Deploy S3 stacks.

    ```sh
    $ rain deploy s3-buckets-for-io.cfn.yml s3-buckets-for-io
    ```
