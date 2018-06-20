---
name: AWS EC2 Systems Manager
x-slug: aws-ec2-systems-manager
description: Amazon EC2 Systems Manager is a management service that helps you automatically
  collect software inventory, apply OS patches, create system images, and configure
  Windows and Linux operating systems. These capabilities help you define and track
  system configurations, prevent drift, and maintain software compliance of your EC2
  and on-premises configurations. By providing a management approach that is designed
  for the scale and agility of the cloud but extends into your on-premises data center,
  EC2 Systems Manager makes it easier for you to seamlessly bridge your existing infrastructure
  with AWS.EC2 Systems Manager is easy to use. Simply access EC2 Systems Manager from
  the EC2 Management Console, select the instances you want to manage, and define
  the management tasks you want to perform. EC2 Systems Manager is available now at
  no cost to manage both your EC2 and on-premises resources.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS EC2 Systems Manager
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon EC2 Systems Manager API Add Tags To Resource
  x-api-slug: amazon-ec2-systems-manager-api
  description: Adds or overwrites one or more tags for the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=AddTagsToResource
  tags: Resources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionaddtagstoresource-get-openapi.md
- name: Amazon EC2 Systems Manager API Cancel Command
  x-api-slug: amazon-ec2-systems-manager-api
  description: Attempts to cancel the command specified by the Command ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=CancelCommand
  tags: Cancel, Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncancelcommand-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncancelcommand-get-openapi.md
- name: Amazon EC2 Systems Manager API Create Activation
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Registers your on-premises server or virtual machine with Amazon EC2 so that you can manage
       these resources using Run Command.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=CreateActivation
  tags: Activation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreateactivation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreateactivation-get-openapi.md
- name: Amazon EC2 Systems Manager API Create Association
  x-api-slug: amazon-ec2-systems-manager-api
  description: Associates the specified SSM document with the specified instances
    or targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=CreateAssociation
  tags: Association
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreateassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreateassociation-get-openapi.md
- name: Amazon EC2 Systems Manager API Create Association Batch
  x-api-slug: amazon-ec2-systems-manager-api
  description: Associates the specified SSM document with the specified instances
    or targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=CreateAssociationBatch
  tags: Association, Batch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreateassociationbatch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreateassociationbatch-get-openapi.md
- name: Amazon EC2 Systems Manager API Create Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: Creates an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=CreateDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreatedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreatedocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Create Maintenance Window
  x-api-slug: amazon-ec2-systems-manager-api
  description: Creates a new Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=CreateMaintenanceWindow
  tags: Maintenance, Window
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreatemaintenancewindow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreatemaintenancewindow-get-openapi.md
- name: Amazon EC2 Systems Manager API Create Patch Baseline
  x-api-slug: amazon-ec2-systems-manager-api
  description: Creates a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=CreatePatchBaseline
  tags: Baseline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreatepatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actioncreatepatchbaseline-get-openapi.md
- name: Amazon EC2 Systems Manager API Delete Activation
  x-api-slug: amazon-ec2-systems-manager-api
  description: Deletes an activation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeleteActivation
  tags: Activation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeleteactivation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeleteactivation-get-openapi.md
- name: Amazon EC2 Systems Manager API Delete Association
  x-api-slug: amazon-ec2-systems-manager-api
  description: Disassociates the specified SSM document from the specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeleteAssociation
  tags: Association
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeleteassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeleteassociation-get-openapi.md
- name: Amazon EC2 Systems Manager API Delete Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: Deletes the SSM document and all instance associations to the document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeleteDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeletedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeletedocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Delete Maintenance Window
  x-api-slug: amazon-ec2-systems-manager-api
  description: Deletes a Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeleteMaintenanceWindow
  tags: Maintenance, Window
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeletemaintenancewindow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeletemaintenancewindow-get-openapi.md
- name: Amazon EC2 Systems Manager API Delete Parameter
  x-api-slug: amazon-ec2-systems-manager-api
  description: Delete a parameter from the system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeleteParameter
  tags: Parameter
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeleteparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeleteparameter-get-openapi.md
- name: Amazon EC2 Systems Manager API Delete Patch Baseline
  x-api-slug: amazon-ec2-systems-manager-api
  description: Deletes a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeletePatchBaseline
  tags: Baseline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeletepatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondeletepatchbaseline-get-openapi.md
- name: Amazon EC2 Systems Manager API Deregister Managed Instance
  x-api-slug: amazon-ec2-systems-manager-api
  description: Removes the server or virtual machine from the list of registered servers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeregisterManagedInstance
  tags: Deregister, Managed, Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionderegistermanagedinstance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionderegistermanagedinstance-get-openapi.md
- name: Amazon EC2 Systems Manager API Deregister Patch Baseline For Patch Group
  x-api-slug: amazon-ec2-systems-manager-api
  description: Removes a patch group from a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeregisterPatchBaselineForPatchGroup
  tags: Deregister, BaselineGroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionderegisterpatchbaselineforpatchgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionderegisterpatchbaselineforpatchgroup-get-openapi.md
- name: Amazon EC2 Systems Manager API Deregister Target From Maintenance Window
  x-api-slug: amazon-ec2-systems-manager-api
  description: Removes a target from a Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeregisterTargetFromMaintenanceWindow
  tags: Deregister, Target, From, Maintenance, Window
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionderegistertargetfrommaintenancewindow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionderegistertargetfrommaintenancewindow-get-openapi.md
- name: Amazon EC2 Systems Manager API Deregister Task From Maintenance Window
  x-api-slug: amazon-ec2-systems-manager-api
  description: Removes a task from a Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeregisterTaskFromMaintenanceWindow
  tags: Deregister, Task, From, Maintenance, Window
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionderegistertaskfrommaintenancewindow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionderegistertaskfrommaintenancewindow-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Activations
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeActivations
  tags: Activations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Association
  x-api-slug: amazon-ec2-systems-manager-api
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeAssociation
  tags: Association
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Automation Executions
  x-api-slug: amazon-ec2-systems-manager-api
  description: Provides details about all active and terminated Automation executions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeAutomationExecutions
  tags: Automation, Executions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeautomationexecutions-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Available Patches
  x-api-slug: amazon-ec2-systems-manager-api
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeAvailablePatches
  tags: Available, Patches
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Document Permission
  x-api-slug: amazon-ec2-systems-manager-api
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeDocumentPermission
  tags: Document, Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Effective Instance Associations
  x-api-slug: amazon-ec2-systems-manager-api
  description: All associations for the instance(s).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeEffectiveInstanceAssociations
  tags: Effective, Instance, Associations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeeffectiveinstanceassociations-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Effective Patches For Patch Baseline
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeEffectivePatchesForPatchBaseline
  tags: Effective, PatchesBaseline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Instance Associations Status
  x-api-slug: amazon-ec2-systems-manager-api
  description: The status of the associations for the instance(s).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeInstanceAssociationsStatus
  tags: Instance, Associations, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceassociationsstatus-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Instance Information
  x-api-slug: amazon-ec2-systems-manager-api
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeInstanceInformation
  tags: Instance, Information
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Instance Patches
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeInstancePatches
  tags: Instance, Patches
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Instance Patch States
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves the high-level patch state of one or more instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeInstancePatchStates
  tags: Instance, States
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatchstates-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Instance Patch States For Patch Group
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves the high-level patch state for the instances in the specified
    patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeInstancePatchStatesForPatchGroup
  tags: Instance, StatesGroup
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatchstatesforpatchgroup-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Window Executions
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Lists the executions of a Maintenance Window (meaning, information about when the
       Maintenance Window was scheduled to be active and information about tasks registered and run with
       the Maintenance Window).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindowExecutions
  tags: Maintenance, Window, Executions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutions-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Window Execution Task
    Invocations
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindowExecutionTaskInvocations
  tags: Maintenance, Window, Execution, Task, Invocations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Window Execution Tasks
  x-api-slug: amazon-ec2-systems-manager-api
  description: For a given Maintenance Window execution, lists the tasks that were
    executed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindowExecutionTasks
  tags: Maintenance, Window, Execution, Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontasks-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Windows
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindows
  tags: Maintenance, Windows
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Window Targets
  x-api-slug: amazon-ec2-systems-manager-api
  description: Lists the targets registered with the Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindowTargets
  tags: Maintenance, Window, Targets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowtargets-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Window Tasks
  x-api-slug: amazon-ec2-systems-manager-api
  description: Lists the tasks in a Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindowTasks
  tags: Maintenance, Window, Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowtasks-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Parameters
  x-api-slug: amazon-ec2-systems-manager-api
  description: Get information about a parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeParameters
  tags: Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribeparameters-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Patch Baselines
  x-api-slug: amazon-ec2-systems-manager-api
  description: Lists the patch baselines in your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribePatchBaselines
  tags: Baselines
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribepatchbaselines-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Patch Groups
  x-api-slug: amazon-ec2-systems-manager-api
  description: Lists all patch groups that have been registered with patch baselines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribePatchGroups
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroups-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Patch Group State
  x-api-slug: amazon-ec2-systems-manager-api
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribePatchGroupState
  tags: Group, State
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Automation Execution
  x-api-slug: amazon-ec2-systems-manager-api
  description: Get detailed information about a particular Automation execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetAutomationExecution
  tags: Automation, Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetautomationexecution-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Command Invocation
  x-api-slug: amazon-ec2-systems-manager-api
  description: Returns detailed information about command execution for an invocation
    or plugin.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetCommandInvocation
  tags: Command, Invocation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetcommandinvocation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetcommandinvocation-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Default Patch Baseline
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves the default patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetDefaultPatchBaseline
  tags: Default, Baseline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetdefaultpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetdefaultpatchbaseline-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Deployable Patch Snapshot For Instance
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves the current snapshot for the patch baseline the instance
    uses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetDeployablePatchSnapshotForInstance
  tags: Deployable, SnapshotInstance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetdeployablepatchsnapshotforinstance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetdeployablepatchsnapshotforinstance-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: Gets the contents of the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetdocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetdocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Inventory
  x-api-slug: amazon-ec2-systems-manager-api
  description: Query inventory information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetInventory
  tags: Inventory
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetinventory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetinventory-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Inventory Schema
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Return a list of inventory type names for the account, or return a list of attribute
       names for a specific Inventory item type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetInventorySchema
  tags: Inventory, Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetinventoryschema-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Maintenance Window
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves a Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetMaintenanceWindow
  tags: Maintenance, Window
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindow-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Maintenance Window Execution
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Retrieves details about a specific task executed as part of a Maintenance Window
       execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetMaintenanceWindowExecution
  tags: Maintenance, Window, Execution
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecution-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Maintenance Window Execution Task
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Retrieves the details about a specific task executed as part of a Maintenance Window
       execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetMaintenanceWindowExecutionTask
  tags: Maintenance, Window, Execution, Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecutiontask-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecutiontask-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Parameter History
  x-api-slug: amazon-ec2-systems-manager-api
  description: Query a list of all parameters used by the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetParameterHistory
  tags: Parameter, History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetparameterhistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetparameterhistory-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Parameters
  x-api-slug: amazon-ec2-systems-manager-api
  description: Get a list of parameters used by the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetParameters
  tags: Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetparameters-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Patch Baseline
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves information about a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetPatchBaseline
  tags: Baseline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetpatchbaseline-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Patch Baseline For Patch Group
  x-api-slug: amazon-ec2-systems-manager-api
  description: Retrieves the patch baseline that should be used for the specified
    patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetPatchBaselineForPatchGroup
  tags: BaselineGroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetpatchbaselineforpatchgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actiongetpatchbaselineforpatchgroup-get-openapi.md
- name: Amazon EC2 Systems Manager API List Associations
  x-api-slug: amazon-ec2-systems-manager-api
  description: Lists the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListAssociations
  tags: List, Associations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionlistassociations-get-openapi.md
- name: Amazon EC2 Systems Manager API List Command Invocations
  x-api-slug: amazon-ec2-systems-manager-api
  description: An invocation is copy of a command sent to a specific instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListCommandInvocations
  tags: List, Command, Invocations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionlistcommandinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionlistcommandinvocations-get-openapi.md
- name: Amazon EC2 Systems Manager API List Commands
  x-api-slug: amazon-ec2-systems-manager-api
  description: Lists the commands requested by users of the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListCommands
  tags: List, Commands
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionlistcommands-get-openapi.md
- name: Amazon EC2 Systems Manager API List Documents
  x-api-slug: amazon-ec2-systems-manager-api
  description: Describes one or more of your SSM documents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListDocuments
  tags: List, Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionlistdocuments-get-openapi.md
- name: Amazon EC2 Systems Manager API List Document Versions
  x-api-slug: amazon-ec2-systems-manager-api
  description: List all versions for a document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListDocumentVersions
  tags: List, Document, Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionlistdocumentversions-get-openapi.md
- name: Amazon EC2 Systems Manager API List Inventory Entries
  x-api-slug: amazon-ec2-systems-manager-api
  description: A list of inventory items returned by the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListInventoryEntries
  tags: List, Inventory, Entries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionlistinventoryentries-get-openapi.md
- name: Amazon EC2 Systems Manager API List Tags For Resource
  x-api-slug: amazon-ec2-systems-manager-api
  description: Returns a list of the tags assigned to the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListTagsForResource
  tags: List, TagsResource
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionlisttagsforresource-get-openapi.md
- name: Amazon EC2 Systems Manager API Modify Document Permission
  x-api-slug: amazon-ec2-systems-manager-api
  description: Share a document publicly or privately.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ModifyDocumentPermission
  tags: Modify, Document, Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionmodifydocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionmodifydocumentpermission-get-openapi.md
- name: Amazon EC2 Systems Manager API Put Inventory
  x-api-slug: amazon-ec2-systems-manager-api
  description: Bulk update custom inventory items on one more instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=PutInventory
  tags: Inventory
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionputinventory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionputinventory-get-openapi.md
- name: Amazon EC2 Systems Manager API Put Parameter
  x-api-slug: amazon-ec2-systems-manager-api
  description: Add one or more paramaters to the system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=PutParameter
  tags: Parameter
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionputparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionputparameter-get-openapi.md
- name: Amazon EC2 Systems Manager API Register Default Patch Baseline
  x-api-slug: amazon-ec2-systems-manager-api
  description: Defines the default patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=RegisterDefaultPatchBaseline
  tags: Register, Default, Baseline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionregisterdefaultpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionregisterdefaultpatchbaseline-get-openapi.md
- name: Amazon EC2 Systems Manager API Register Patch Baseline For Patch Group
  x-api-slug: amazon-ec2-systems-manager-api
  description: Registers a patch baseline for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=RegisterPatchBaselineForPatchGroup
  tags: Register, BaselineGroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionregisterpatchbaselineforpatchgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionregisterpatchbaselineforpatchgroup-get-openapi.md
- name: Amazon EC2 Systems Manager API Register Target With Maintenance Window
  x-api-slug: amazon-ec2-systems-manager-api
  description: Registers a target with a Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=RegisterTargetWithMaintenanceWindow
  tags: Register, TargetMaintenance, Window
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionregistertargetwithmaintenancewindow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionregistertargetwithmaintenancewindow-get-openapi.md
- name: Amazon EC2 Systems Manager API Register Task With Maintenance Window
  x-api-slug: amazon-ec2-systems-manager-api
  description: Adds a new task to a Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=RegisterTaskWithMaintenanceWindow
  tags: Register, TaskMaintenance, Window
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionregistertaskwithmaintenancewindow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionregistertaskwithmaintenancewindow-get-openapi.md
- name: Amazon EC2 Systems Manager API Remove Tags From Resource
  x-api-slug: amazon-ec2-systems-manager-api
  description: Removes all tags from the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=RemoveTagsFromResource
  tags: Remove, Tags, From, Resource
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionremovetagsfromresource-get-openapi.md
- name: Amazon EC2 Systems Manager API Send Command
  x-api-slug: amazon-ec2-systems-manager-api
  description: Executes commands on one or more remote instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=SendCommand
  tags: Send, Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionsendcommand-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionsendcommand-get-openapi.md
- name: Amazon EC2 Systems Manager API Start Automation Execution
  x-api-slug: amazon-ec2-systems-manager-api
  description: Initiates execution of an Automation document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=StartAutomationExecution
  tags: Start, Automation, Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionstartautomationexecution-get-openapi.md
- name: Amazon EC2 Systems Manager API Stop Automation Execution
  x-api-slug: amazon-ec2-systems-manager-api
  description: Stop an Automation that is currently executing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=StopAutomationExecution
  tags: Stop, Automation, Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionstopautomationexecution-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Association
  x-api-slug: amazon-ec2-systems-manager-api
  description: Updates an association.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdateAssociation
  tags: Association
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdateassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdateassociation-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Association Status
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Updates the status of the SSM document associated with the specified
       instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdateAssociationStatus
  tags: Association, Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdateassociationstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdateassociationstatus-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: The document you want to update.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdateDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatedocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Document Default Version
  x-api-slug: amazon-ec2-systems-manager-api
  description: Set the default version of a document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdateDocumentDefaultVersion
  tags: Document, Default, Version
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatedocumentdefaultversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatedocumentdefaultversion-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Maintenance Window
  x-api-slug: amazon-ec2-systems-manager-api
  description: Updates an existing Maintenance Window.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdateMaintenanceWindow
  tags: Maintenance, Window
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatemaintenancewindow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatemaintenancewindow-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Managed Instance Role
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Assigns or changes an Amazon Identity and Access Management (IAM) role to the managed
       instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdateManagedInstanceRole
  tags: Managed, Instance, Role
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatemanagedinstancerole-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatemanagedinstancerole-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Patch Baseline
  x-api-slug: amazon-ec2-systems-manager-api
  description: Modifies an existing patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdatePatchBaseline
  tags: Baseline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatepatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/actionupdatepatchbaseline-get-openapi.md
- name: Amazon EC2 Systems Manager API
  x-api-slug: amazon-ec2-systems-manager-api
  description: Amazon EC2 Systems Manager is a management service that helps you automatically
    collect software inventory, apply OS patches, create system images, and configure
    Windows and Linux operating systems. These capabilities help you define and track
    system configurations, prevent drift, and maintain software compliance of your
    EC2 and on-premises configurations. By providing a management approach that is
    designed for the scale and agility of the cloud but extends into your on-premises
    data center, EC2 Systems Manager makes it easier for you to seamlessly bridge
    your existing infrastructure with AWS.EC2 Systems Manager is easy to use. Simply
    access EC2 Systems Manager from the EC2 Management Console, select the instances
    you want to manage, and define the management tasks you want to perform. EC2 Systems
    Manager is available now at no cost to manage both your EC2 and on-premises resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: AWS EC2 Systems Manager
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-systems-manager/master/_listings/aws-ec2-systems-manager/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/ssm/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/systems-manager/faqs/
- type: x-getting-started
  url: http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/systems-manager.html
- type: x-website
  url: https://aws.amazon.com/ec2/systems-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---