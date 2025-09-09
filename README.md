# Terraform with Azure - Complete Video Course 🚀

Welcome to the comprehensive Terraform with Azure video course! This repository contains all code samples and documentation corresponding to each video lesson.

## 🎯 Course Overview
This course consists of video lessons covering basic to advanced Terraform concepts with Azure cloud, including hands-on projects and real-world scenarios.

Note: If you found the content helpful, consider giving the repository a star ⭐

## 🔗 Join our community 👇


<a href="https://youtube.com/@techtutorialswithpiyush"><img src="https://www.freeiconspng.com/thumbs/youtube-icon/video-youtube-icon--14.png" height="60px"></img></a>
<a href="https://discord.com/invite/FMtJ2bVRUE"><img src="https://img.icons8.com/color/2x/discord--v2.png" height="60px"></img></a>
<a href="https://github.com/piyushsachdeva/"><img src="https://user-images.githubusercontent.com/91791257/235086411-9ec7aa5e-c095-44ce-b9e6-57b3bc3fead2.png" height="60px"></img></a>
<a href="https://twitter.com/thecloudopscomm"><img src="https://i.postimg.cc/pVqVTNJd/X-logo.png" height="60px"></img></a>
<a href="https://www.linkedin.com/company/thecloudopscomm/"><img src="https://img.icons8.com/fluency/2x/linkedin.png" height="60px"></img></a>
<a href="https://www.instagram.com/techtutorialswithpiyush/"><img src="https://user-images.githubusercontent.com/91791257/235086447-47658b7b-71fa-4baf-830a-3ba9b3a76a47.png" height="60px"></img></a>

## 📋 Prerequisites
- Azure free account or subscription, follow this [video](https://youtu.be/bv3CWyaUeJI)
- Azure Fundamentals [Video Link](https://youtu.be/-pX5PjIYTJs)
- Visual Studio Code or preferred IDE
- Git installed and working knowledge of it
- Linux or Mac or WSL(Windows Subsystem for Linux)
- Linux and Shell scripting
- Basic understanding of YAML and JSON
- Networking Fundamentals
- IP Addressing [Video Link](https://youtu.be/G1azmL5-eQI)
- Docker and Kubernetes Fundamentals [Playlist Link](https://www.youtube.com/playlist?list=PLl4APkPHzsUUOkOv3i62UidrLmSB8DcGC)

## 📚 Course Curriculum

### Module 1: Core Concepts

#### Day1: [![Introduction to Terraform](https://img.youtube.com/vi/j0mfH_7sR7k/sddefault.jpg)](https://youtu.be/j0mfH_7sR7k)
- Understanding Infrastructure as Code (IaC)
- Why we need IaC
- What is Terraform and its benefits
- Challenges with the traditional approach
- Terraform Workflow
- Installing Terraform
- [Code Sample](/lessons/day01/)

#### Day2: Terraform Provider
- Terraform Providers
- Provider version v/s Terraform core version
- Why version matters
- Version constraints
- Operators for versions
- [Code Sample](/lessons/day02/)

#### Day3: Resource Group and Storage Account
- Authentication and Authorization to Azure resources
- Creating resource groups
- Storage account management
- Understanding dependencies
- [Code Sample](/lessons/day03/)

#### Day4: State file management - Remote Backend
- How Terraform updates Infra
- Terraform state file
- State file best practices
- Remote backend setup
- State management
- [Code Sample](/lessons/day04/)

#### Day5: Variables
- Input variables
- Output variables
- Locals
- Variable precedence
- Variable files (tfvars)
- [Code Sample](/lessons/day05/)

#### Day6: File Structure
- Terraform file organization
- Sequence of file loading
- Best practices for structure
- [Code Sample](/lessons/day06/)

#### Video 7: Type constraints in Terraform
- String, number, bol
- Map, set, list, Tuple, Objects
- [Code Sample](/lessons/day07/)

#### Video 8: Meta-arguments
- Understanding count
- for_each loop
- for loop
- Practical examples
- [Code Sample](/lessons/day08)

#### Video 9: The Lifecycle meta-arguments
- create before destroy
- prevent destroy
- ignore changes
- replace triggered by
- customer condition
- [Code Sample](/lessons/day09)

#### Video 10: Dynamic Blocks and expressions
- Dynamic blocks
- Conditional expressions
- Splat Expressions
- practical examples
- [Code Sample](/lessons/day10)

#### Video 11: Functions in Terraform
- Built-in functions
- Practical examples
- tasks for practice
- [Code Sample](/lessons/day11)


#### Video 12: Functions in Terraform(Continue..)
- Built-in functions
- Practical examples
- tasks for practice
- [Code Sample](/lessons/day12)

#### Video 13: Data Sources
- Using data sources
- Practical examples
- [Code Sample](/lessons/day13)
  
### Module 2: Azure resources using Terraform 

#### Video 14: High available/scalable Infrastructure Deployment ( Mini Project 1 )
- Creating Virtual Machines
- VM Scale Sets
- Network Security Groups
- Loadbalancer, Nat Gateway, Public IP , Autoscaling rules etc
- [Code Sample](/lessons/day14)

#### Video 15: VNET and Peering ( Mini Project 2 )
- Virtual Network Creation
- VNet peering setup
- [Code Sample](/lessons/day15)

#### Video 16: Azure AD Authentication ( Mini Project 3 )
- Authentication methods
- Service principals
- Managed identities
- [Code Sample](/lessons/day16)

#### Video 17: Azure Web Apps ( Mini Project 4 )
- App Service creation
- Configuration
- Deployment
- [Code Sample](/lessons/day17)

#### Video 18: Azure Functions ( Mini Project 5 )
- Function App setup
- Configuration
- [Code Sample](/lessons/day18)

#### Video 19: Terraform Provisioners ( Mini Project 6 )
- What are provisioners and their use case
- Local vs remote vs file provisioners
- Demo of all three provisioners
- [Code Sample](/lessons/day19)

#### Video 20: AKS Cluster ( Real-time Project 1)
- Kubernetes cluster setup
- Custom module usage
- Custom module creation for AKS, KeyVault, SPN etc
- [Code Sample](/lessons/day20)

#### Video 21: Azure Policy and Governance ( Mini Project 7 )
- Policy creation
- Governance setup
- [Code Sample](/lessons/day21)


#### Video 22: Azure SQL Database ( Mini Project 8 )
- Database creation
- Configuration
- [Code Sample](/lessons/day22)

#### Video 23: Azure Monitoring ( Mini Project 9 )
- Metrics alerts
- Action Groups
- Log analytics workspace
- Log alerts
- [Code Sample](/lessons/day23)

### Module 3: Advanced Concepts

#### Video 24: Terraform Import (Real-time project 2)
- Different ways of importing Azure resource to Terraform
- Terraform Import
- Importing a live website to Terraform using Terraform Import
- AZExport
- Importing a live website to Terraform using AZExport
- Terraformer
- [Code Sample](/lessons/day24)

#### Video 25: Terraform Cloud and Workspaces
- Cloud setup
- Workspace management
- [Code Sample](/lessons/day25)

#### Video 26: Azure DevOps with Terraform (Real-time project 3)
- CI/CD pipeline setup
- Automation
- [Code Sample](/lessons/day26)

#### Video 27: 3-Tier Architecture (Real-time project 4)
- Complete architecture setup
- Best practices
- [Code Sample](/lessons/day27)

#### Video 28:  Terraform end-to-end Project with AKS and GitOps (Real-time project 5)
- Diagram and flow
- Code walkthrough
- Implementation
- [Code Sample](/lessons/day28)




## 📂 Repository Structure
```
├── lessons/
│   ├── day01/
│   ├── day02/
│   └── ...
├── docs/
│   ├── setup.md
│   └── troubleshooting.md
└── README.md
```

## 🎓 Learning Path
1. Follow videos in sequence
2. Complete hands-on exercises
3. Implement projects
4. Practice with provided code samples

## 📝 License
MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Resources
- [Terraform Documentation](https://www.terraform.io/docs)
- [Azure Documentation](https://docs.microsoft.com/azure)
- [Course Support Forum]()
