# Demonstration of Prisma VS Code extension bug when handling nested schema folders

This repository demonstrates the issue described at https://github.com/prisma/language-tools/issues/1803

## How to reproduce

1. Clone the repository at https://github.com/tom-groves/prisma-extension-nested-schema-folders-example
2. Open in VS Code
3. Running `npx prisma generate` will generate the Prisma Client successfully
4. Nested Prisma schemas, such as `src/modules/company/company.prisma`, will be in an error state
