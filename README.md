# SAP_Basis_Course
**1st Chapter:Creation of Role**:

In SAP, we use T-code for roles creation type:PFCG and type name convention.
**For example**

zm_master_role and zd_derive_role

**Limit**
30 characteristics

There are serveral types of roles in SAP/S4.

1.Single Role

2.Composite role(group of role)

3.Fiori Role(Develop by Abap Develop)

But now a days, Only two roles are working in industry.

Master Roles
Derive Roles

**Master Roles**: Contain non-org values and authorization object and Transaction.
        

**Derive Role** :Derived role is basically derived from master which contain only org values and assign to the user.**

**Execution of Role in SAP****

Execute by PFCG

**Benefit of Master derived role**

1.Multiple company / Multiple plants

2.Single company / Multiple Plants

3.For maintain large scale company

4.HR – Salaries

5.Finance – GL, accounts etc.

**Chapter 2 :User creation**
In SAP, there are few step for creation a user.

First, we login to SAP.

Second, execute t-code which is Su01

**Suggestion a name of user**:zoh12po

Click on create button

Fill all required field for username/Lastname, password and assign the role of particular user.

After creating a user, we select a user which has been created and click on change button

Below mention ss are given below.
![image](https://github.com/IBEZ/SAP_Basis_Course/assets/15713295/cb913881-ee34-40aa-9331-b02dccc93784)

**Chapter 3:Client copy and Host file**

Sometime, while consultant on client premises,they require a host to maintain in consultant laptop or user/end user so, they need that type of host file to maintain in they laptop

**Directory in Window**

Path:  C:\Windows\System32\drivers\etc

**Client copy**
Transferring client specific data within the same system / between different system.

**Purpose**
Why we need client copy?
For a testing purpose

**Host file**
Host file is an operating system files that map a hostname to IP address. It is a plain text file.




