# vim_filters
> :%!python3 -m json.tool

![image](https://github.com/theshpio/tricks/assets/161257754/c1b5537f-fd8a-4365-be1a-5bb57267e4f1)

### result:

![image](https://github.com/theshpio/tricks/assets/161257754/640ac908-aba1-4575-a47b-d3147e4b99f8)

> :%!python3 -c "import json, sys; print(json.dumps(json.load(sys.stdin)))"

![image](https://github.com/theshpio/tricks/assets/161257754/7b3ce336-289b-4711-a020-39044d892c96)

### result:

![image](https://github.com/theshpio/tricks/assets/161257754/f230db6a-a29e-4f2e-a910-4f5775c86948)

![image](https://github.com/theshpio/tricks/assets/161257754/6b1b2406-82ab-443a-93c4-05b5f29886d5)

### copy to test
> {"Version": "2012-10-17", "Statement": [{"Sid": "Stmt1", "Effect": "Allow", "Action": "s3:List*", "Resource": "*"}]}
