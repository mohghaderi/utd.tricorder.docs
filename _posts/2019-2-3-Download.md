This project started in 2013 and the development stopped in 2015.
It was intended to be used as a single research application, and 
the main goal was to research new software architectures and innovate software engineering techniques.
Therefore, you may find many technologies are not used the way is used in other projects, 
and in some cases it maybe difficult to understand the design decisions behind it.

In addition, the source code was maintained on Visual Studio Online TFS (Azure DevOps), and it wasn't possible to extract commit history.
DLLs and dependencies pushed to the source control because that was the only way to use VSTS build server back then. 
As a result, I don't expect anyone to easily start using this.

Despite the above facts and some others, I decided to released the source code in case somebody was interested to use it as is.
I am willing to help you with your research project in my free time.

### New version
The upgraded version of this project is fully redesigned according to the best practices and is under development in a private Git repository.
I am planning to open-source that one, too. However, if you're interested to have access to that source earlier, please feel free to email me.

### Pre-requisite
- [Visual Studio Community Edition (2015+)](https://visualstudio.microsoft.com/downloads/)
- [SQL Server Express (2016+)](https://www.microsoft.com/en-us/sql-server/sql-server-editions-express)
- [AWS account](https://aws.amazon.com/) Needed for file uploads or deployments only
- Knowledge of C#, AngularJs, SQL Server

### How to use

To start using the project, you need to download the latest release from [releases](https://github.com/mohghaderi/utd.tricorder/releases).
You can customize the application by modifying the source code. The project doesn't have a separate documentation.

[![Download]({{ site.baseurl }}/images/Download_link_small.png)](https://github.com/mohghaderi/utd.tricorder/releases)

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This source code is released under Public Domain.

