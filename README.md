# PubliNews

PubliNews is a free and open-source news aggregator which works with different public APIs to grab latest news from your favourite social networks.

## What can it do?

PubliNews can give you opportunity to:

- Select sources for grabbing news
- Grab news for this day from different public networks
- Edit to change grabbed news
- Have a main page with notes that you published

More you can see from ER diagram, Component diagram and use cases, and pictures-sketches in pictures/ folder.

Social networks available for news scraping:

- Facebook
- Twitter
- Tumblr

## Roadmap

Todo list:

- [x] Database part of application
  - [x] Set up PostgreSQL database
  - [x] Create schema
  - [x] Build Entity-Relation Diagram
- [x] Server side of application
  - [x] Work with query-builder Knex.js
  - [x] Create routes with Express.js
  - [x] Establish API connection to social networks
- [x] Frontend side of application
  - [x] Build basic GUI
  - [x] Use React.js for rendering
  - [ ] Add styles to pages

## Contributing

If you want to help the project but do not code, the best way to help us is to test our application and make bug reports.

If you want to contribute as a developer, please feel free to create pull requests or contact recent contributors.

## Building

```
sudo apt install git

git clone https://github.com/web-nodejs-kpi/publinews-backend.git
git clone https://github.com/web-nodejs-kpi/publinews-frontend.git

# Run backend
cd ./publinews-backend
npm start

# Run frontend
cd ./publinews-frontend
npm start

```

## License

All files in all repositories are licensed under the terms of MIT license.
