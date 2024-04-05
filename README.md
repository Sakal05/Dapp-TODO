# ToDo DApp

This project consists of a frontend application and a smart contract for managing a to-do list on the Ethereum blockchain. The application allows users to create tasks, mark them as completed, and share them with other Ethereum addresses. Below is a brief overview of the project's functionality and validation.

## Frontend Functionality
- **Connect Wallet**: Allows users to connect their Ethereum wallet to the application.
- **Display User Information**: Displays the user's address and wallet balance.
- **Display Tasks**: Shows tasks owned by the user, including task ID, name, and completion status.
- **Create New Task**: Enables users to create new tasks, optionally sharing them with other Ethereum addresses.
- **Mark Task as Complete**: Allows users to mark their own tasks as completed.
- **Display Shared Tasks**: Shows tasks shared with the user by other Ethereum addresses, including task ID, name, and completion status.
- **Mark Shared Task as Complete**: Allows users to mark shared tasks as completed.

## Smart Contract Functionality
- **Create Task**: Allows users to create new tasks, which are stored on the blockchain. Optionally, users can share tasks with other Ethereum addresses.
- **Get My Tasks**: Retrieves tasks owned by a specific Ethereum address.
- **Mark Task as Completed**: Allows the owner of a task or a shared user to mark the task as completed.
#### Additional
- **Get Shared Tasks**: Retrieves tasks shared with a specific Ethereum address by other users.

## Validation
- **Authorization**: Certain functions are restricted to the owner of the task or shared users, ensuring that only authorized individuals can perform specific actions.
- **Task Completion**: Prevents users from marking tasks as completed multiple times.
- **Invalid Address Handling**: Validates Ethereum addresses to prevent errors during task sharing.

### Smart Contract Address
- **Deployed Address**: [0x15138a8Ab6B71AbC786F3EDae0B46a93F0Bd7B7f](https://sepolia.etherscan.io/address/0x15138a8Ab6B71AbC786F3EDae0B46a93F0Bd7B7f#code)

### Frontend Application
- **Vercel Link**: [ToDo DApp Frontend](https://todo-dapp-frontend-sakal.vercel.app/)

This application provides a simple yet effective way for users to manage their tasks on the Ethereum blockchain, ensuring transparency and immutability of task data.
