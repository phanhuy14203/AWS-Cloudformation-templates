# AWS-Cloudformation-templates
## Steps to Submit Create Stack
### Step 1: Log in to AWS Management Console
1. Go to the AWS Management Console.
2. Log in using your AWS account credentials.
### Step 2: Open the CloudFormation Service
1. In the console, search for and select **CloudFormation** from the list of services.
### Step 3: Create a New Stack
1. Click on the **Create stack** button.
2. Choose **With new resources (standard)**.
### Step 4: Upload the YAML File
1. In the **Specify template** section, you have three options:
* **Upload a template file**: Select this option to upload the YAML file from your computer.
* **Amazon S3 URL**: If your YAML file is already uploaded to S3, you can enter its URL here.
* **Sample templates**: Choose from the available sample templates.
2. If you select **Upload a template file**, click **Choose file** and select the YAML file from your computer.
### Step 5: Enter Stack Information
1. Click **Next**.
2. Enter a name for the stack in the **Stack name** field.
3. If your YAML file has parameters, you will see fields to enter values for them. Provide the required values
### Step 6: Configure Stack Options
1. Click **Next**.
2. You can configure additional options such as:
* **Tags**: Add tags for the stack.
* **IAM role**: Select an IAM role if needed.
* **Advanced options**: Configure any advanced options as necessary.
### Step 7: Review and Create Stack
1. Click **Next**.
2. Review all the information you have entered.
3. Check the box **I acknowledge that AWS CloudFormation might create IAM resources** if your template creates IAM resources.
4. Click **Create stack**.
### Step 8: Monitor the Stack Creation Process
1. After clicking **Create stack**, you will be redirected to the **Stacks** page.
2. Here, you can monitor the status of your stack. When the process is complete, the status will change to **CREATE_COMPLETE**.
## 📌NOTE
* If there are errors during the stack creation process, you can click on the stack name to view detailed error messages in the **Events** tab.
* Ensure that you have the appropriate IAM permissions to create the resources specified in your YAML file.

