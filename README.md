## Project

Happy is a project developed from the International Children's Day that takes place on October 12th.

The goal is to create an application where you can find and visit orphanages.

## Technologies

This project was developed with the following technologies:

- [Node.js 14.21.3](https://nodejs.org)
- [TypeScript](https://www.typescriptlang.org)

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org) installed on your computer.

From your command line:

```bash
# Clone this repository

$ git clone https://github.com/joeldorosarioo/happy-platform-server.git

$ cd happy-platform-server

# Install dependencies

$ yarn install

# Activate hooks

$ yarn husky install

# If you want to recreate the database run the following migrates

$ yarn typeorm migration:run

# Start the Server

$ yarn start

# Access: http://localhost:3333/orphanages to view all Orphanages registered so far
```

## How to contribute

- Make a fork;
- Create a branck with your feature: `git checkout -b my-feature`;
- Commit changes: `git commit -m 'feat: My new feature'`;
- Make a push to your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## License

This project is under the MIT license. See the [LICENSE](/LICENSE) for details.
