# Tech Stack
Below is a variety of technologies, software packages, and environments that are actively used or in consideration for this project. They are organized into the following categories:

- **Backend:** technologies used to enable infrastructure, data storage, and server-side run-times
- **Frontend:** technologies used to deliver the user interface
- **APIs:** technologies used to interact with the backend, including through the frontend or to bypass the frontend
- **Development Environment:** technologies used locally by software engineers to develop the project

Each of these categories contain a table with technologies that are specific to that category. Each table assigns an ID to the technology for quick reference, a short description, a link to another markdown document with further details on the technology, and includes the status of the technology within this project. The statuses break down as follows:

- Discovered: the technology has been added to the list for reference. It may never leave this status
- *In Consideration:* the technology is being furthered investigated to be incorporated into the project and may be compared against other similar options
- **Chosen:** the technology has been selected for use and is needs to be integrated into the project
- ==Integrated:== the technology is actively used in the project
- ~~Deprecated:~~ the technology was in use in the project at one point in time but has since been removed, either due to being replaced by a similar option or becoming unnecessary

## Backend

| ID | Name | Description | Status |
| -: | ---- | ----------- | ------ |
| 0 | [Google Cloud Platform](tech/gcp.md) | Cloud platform for high availability infrastructure | **Chosen** |
| 1 | [Terraform](tech/terraform.md) | IaC tool for maintaining the environment in a stateful manner | **Chosen** |
| 2 | [Tekton](tech/tekton.md) | CI/CD pipeline for testing and deployments | **Chosen** |
| 3 | [GitHub](tech/github.md) | Remote version control tool for maintaining code and resources | **Chosen** |
| 4 | [Docker](tech/docker.md) | Containerized solution for deploying standardized instances of services | *In Consideration* |
| 5 | [Kubernetes](tech/k8s.md) | Distributed container management solution | *In Consideration* |
| 6 | [Python](tech/python.md) | Interpreted scripting language | *In Consideration* |
| 7 | [Go](tech/go.md) | Compiled scripting language | *In Consideration* |
| 8 | [Rust](tech/rust.md) | Compiled scripting language | *In Consideration* |
| 9 | [MongoDB](tech/mongodb.md) | Document-based No-SQL database | *In Consideration* |
| 10 | [Redis](tech/redis.md) | In-memory multi-model database | *In Consideration* |
| 11 | [Dgraph](tech/dgraph.md) | Graph-based database | *In Consideration* |

## Frontend

| ID | Name | Description | Status |
| -: | ---- | ----------- | ------ |
| 0 | [JavaScript](tech/javascript.md) | Scripting language well suited for web applications | **Chosen** |
| 1 | [CSS](tech/css.md) | Document styling for HTML web pages | **Chosen** |
| 2 | [HTML](tech/html.md) | Markup language for displaying web pages | **Chosen** |
| 3 | [React](tech/react.md) | JavaScript framework for delivering modern web applications | *In Consideration* |
| 4 | [Angular](tech/angular.md) | JavaScript framework for delivering modern web applications | *In Consideration* |
| 5 | [Vue.js](tech/vuejs.md) | JavaScript framework for delivering modern web applications | *In Consideration* |
| 6 | [TypeScript](tech/typescript.ms) | Language on top of JavaScript for faster and more reliable development | *In Consideration* |

## APIs

| ID | Name | Description | Status |
| -: | ---- | ----------- | ------ |
| 0 | [GraphQL](tech/graphql.md) | API tool set | *In Consideration* |
| 1 | [REST](tech/rest.md) | API standards for HTTP-based communication and responses | *In Consideration* |

## Development Environment

| ID | Name | Description | Status |
| -: | ---- | ----------- | ------ |
| 0 | [VS Code](tech/vscode.md) | Lightweight and extendable development environment | ==Integrated== |
| 1 | [Git](tech/git.md) | Version control for maintaining code and resource changes locally and remotely | **Chosen** |
| 2 | [Rally](tech/rally.md) | Task management utility for managing user stories and project status | **Chosen** |
| 3 | [Minikube](tech/minikube.md) | Local lightweight Kubernetes cluster for development and testing | *In Consideration* |
| 4 | [StackShare](tech/stackshare.md) | Website for reviewing other tech stacks and technologies used by projects and companies | *In Consideration* |
| 5 | [Cloudcraft](tech/cloudcraft.md) | Website for designing cloud-based architecture for your application | *In Consideration* |