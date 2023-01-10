
**To Initiat and download the plugins**

```$ terraform init```

**To check and Dry run the terraform script**

```$ terraform plan```

**To run terraform script**

```$ terrafomr apply ```

**To delete all the configuration**

```$ terraform destroy ```

**To delete specific resource**
 
```$ terraform destroy -target <aws_instance>.LocalName -target RESOURCE_TYPE2.NAME ```

**To give the commandline value to variable other than default **variables.tf****

```$ terraform plan -var="<Resoucetype>=<value>" ```

```$ terraform plan -var="instancetype=t2.large" ```

**To use the _custome.tf_ variable file**

```$ terrafomr plan --var-file="custome.tf"```

**To appy direct without writting Yes**

```$ terrafomr plan --var-file="custome.tf --auto-approve```

**To set the ENV variable in windows and  Linux**

   **FOR Windows**

``` $ SETX TF_VAR_instancetype m5.large"```
    
   **FOR Linux** 
    
 ``` $ Export TF_VAR_instance="t2.medium"```   
