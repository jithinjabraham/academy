# c02-network05

## Commands Execution Output

- Commands for creating the internet gateway:
```
Add your commands and their outputs here
```
Create IGW
aws ec2 create-internet-gateway --query InternetGateway.InternetGatewayId --output text --tag-specifications 'ResourceType=internet-gateway,Tags=[{Key=Name,Value=ab-dojo-igw}]'

- Any extra challenges faced?


<!-- Don't change anything below this point-->
***
Answer for exercise [c02-network05](https://github.com/devopsacademyau/academy/blob/893381c6f0b69434d9e8597d3d4b1c17f9bc1371/classes/02class/exercises/c02-network05/README.md)