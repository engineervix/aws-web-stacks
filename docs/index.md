# AWS Web Stacks

> this project is a fork of <https://github.com/cactus/aws-web-stacks/>

I forked it in order to customize it to my requirements, which are:

- Use **Ubuntu 20.04 or 18.04** AMIs instead of 16.04
- Possibility of using **Debian Buster** AMIs
- Use the following AWS Regions -- [Africa (Cape Town)](https://aws.amazon.com/blogs/aws/now-open-aws-africa-cape-town-region/) and [Germany (Frankfurt)](https://aws.amazon.com/blogs/aws/aws-region-germany/)
- Use the latest version of Dokku

----

Meanwhile, there's nothing much here, except [this Dokku Cloudformation stack template (JSON)](dokku-no-nat.json). The `.yaml` version is [here](dokku-no-nat.yaml)
