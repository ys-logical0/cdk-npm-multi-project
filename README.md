# AWS CDK with npm Workspaces Sample Project

This repository demonstrates how to set up and manage an AWS Cloud Development Kit (CDK) project within an npm monorepo using workspaces. This setup is ideal for managing multiple CDK stacks or applications in a single repository, promoting modularity and code reuse.

## Project Structure

```bash
root/
├── package.json           # Main package file defining workspaces
├── tsconfig.json          # Shared TypeScript configuration
├── cdk.json               # CDK configuration file
├── packages/
│   ├── project-1/         # First CDK project
│   │   ├── lib/
│   │   ├── bin/
│   │   ├── cdk.json
│   │   └── package.json
│   └── project-2/         # Second CDK project
│       ├── lib/
│       ├── bin/
│       ├── cdk.json
│       └── package.json
└── node_modules/
```

## Contributing
Contributions are welcome! Please fork the repository and create a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.