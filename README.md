# AWS-VPC Full CloudFormation Templates
<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/kkpkishan/aws-full-vpc-cloudformation-templates.git"> FULL VPC (Virtual Private Cloud)</a></h4></th>
    </tr>
    <tr>
        <td width="100%" valign="top">
           <p>Creates an entire VPC from scratch for Lab or Permanent.</p>
           <h6>Create Details</h6>
           <ol>
            <li>Single VPC</li>
            <li>2 Public Subnets</li>
            <li>2 Private Subnets</li>
            <li>2 ALB Subnets</li>
            <li>1 NAT Subnets</li>
            <li>Public Route Table</li>
            <li>Private Route Table</li>
            <li>NAT Route Table</li>
            <li>Internet Gateway</li>
            <ul>
              <li>Attached to the Public Route Table</li>
            </ul>
            <li>NAT Gatway</li>
             <ul>
              <li>Attached to the Private Route Table</li>
            </ul>
                      <td nowrap width="200" valign="top">
            <table>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/home?#/stacks/new?&templateURL=https://electromech-cloudformation-templates.s3.ap-south-1.amazonaws.com/ALB_NAT_vpc_cloudformation_template.yml" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>
                    </td>
                </tr>
            </table>
        </td>
    </tr> 
 </table>

