# Presenting FoRum, the open forum

## Product and Service

- Is the solution feasible and realistic?

### The Problem

China is lacking high-quality knowledge interchange platforms.

### How does FoRum solve The Problem

Observe that,
to have high-quality knowledge interchange on a platform,
we need:

- Users who have high-quality knowledge and are willing to interchange it.
- A platform that helps users interchange information.

Examples include Reddit and
[Stack Overflow](https://stackoverflow.com/questions/7165749/open-file-in-a-relative-location-in-python).

Speculate that,
the reason why China is lacking high-quality knowledge interchange platforms:

- Many users with high-quality knowledge are not willing to interchange it.
- FoRum's competitors do not support high-quality knowledge interchange well.
    - Ad and spammer farm such as
        [Baidu Zhidao](https://zhidao.baidu.com/question/1311735874485709379.html).
    - Lack of proper commenting, upvote, and categorizing mechanisms,
        such as [Jianshu](https://www.jianshu.com/p/3ef5e96c7669).

## Market and Potential Customers

The internet is open to everyone,
therefore anyone willing to interchange knowledge
and have access to the internet
is our potential customer.

University students are a special group.
They have the urge need to interchange knowledge
and they have access to the internet.
This means that the majority of our customers probably will be
university students.

Anyone who is trying to self-teach is also our potential customer.
In this age,
any intelligent people should be learning throughout their lives.
FoRum should be a good platform to help them keep learning.

## Growth Strategy

To help sustain FoRum's "purity" as a knowledge interchange platform,
FoRum shall become a non-profit, not-for-profit, or an organizations of the sort.
FoRum shall avoid Ads and mandatory subscription fees.
Instead, FoRum shall try to operate with a minimum amount of content moderators
and
[rely on the users to moderate the content](https://sichanghe.github.io/doctrine/#basic-approach).

FoRum shall accept donations from customers and organizations.
Such donations can either be subscription-based or one-time.
The donations will be used to pay for the maintenance fees
and FoRum's maintainers' salary.

## Finance

### Server Cost

For deployment,
Amazon Web Services is the best choice.
AWS is the most popular web services provider around the world.
It supports the Chinese region.
And, its services are flexible.

If we choose the lowest-spec machines on AWS:

[Database cost](https://us-east-1.console.aws.amazon.com/rds/home?region=us-east-1#launch-dbinstance:gdb=false;s3-import=false)
is $0.241 per hour.

[Virtual machine cost](https://us-east-1.console.aws.amazon.com/ec2/v2/home?region=us-east-1#LaunchInstances:)
is $0.023 per hour.

In the costs above,
the hours for database cost is calculated
when the database is active,
which I suspect will be about 2 hours per day,
so the price for each month would be $14.46.
The hours for Virtual machine cost is calculated
when the server is on.
If the server is on 24/7,
then the price for each month would be $16.56.
So, the total cost per month would be $31.02.

However, if we choose machines that are suited for production,
then the database cost would be $1.057 per hour
and the virtual machine cost would be $0.0832 per hour,
so the total per month would be around $123.324 per month.
That would be $1479.888 for one year.

### Development Cost
