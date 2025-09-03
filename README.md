### Step 1

The Virtual Private Cloud (VPC) was created with an IPv4 CIDR block of
`10.0.0.0/16`.

<br>

![pic 1](images/1-created-vpc.png)

<br>

---

### Step 2

As shown in the screenshot:

1. Filtered by VPC and selected the custom VPC **`demo-vpc`** created for the project.
2. Created two public subnets:

   - **`PublicSubnetA`** in Availability Zone **`eu-west-2a`** with Subnet CIDR block **`10.0.0.0/24`**
   - **`PublicSubnetB`** in Availability Zone **`eu-west-2b`** with Subnet CIDR block **`10.0.1.0/24`**

   These Subnet CIDR blocks were chosen so that the subnets do not overlap, while remaining within the VPC CIDR block **`10.0.0.0/16`**

<br>

![pic 2](images/2-public-subnets.png)

<br>

---

### Step 3

As shown in the screenshot:

Created two private subnets:

- **`PrivateSubnetA`** in Availability Zone **`eu-west-2a`** with Subnet CIDR block **`10.0.16.0/20`**
- **`PrivateSubnetB`** in Availability Zone **`eu-west-2b`** with Subnet CIDR block **`10.0.32.0/20`**

These Subnet CIDR blocks were chosen so that the subnets do not overlap, while remaining within the VPC CIDR block **`10.0.0.0/16`**

<br>

![pic 3](images/3-private-subnets.png)

<br>
