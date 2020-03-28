# 🚀 RailsBooster

Preconfigured Ruby On Rails Boilerplate To Provide Instant Productivity ⚡️

## 🤓 Motivation behind the project

I regularly keep experimenting with ideas and problems to solve with Ruby On Rails as my choice of stack. However, I find myself configuring Rails as per my preference with every new project to reach to a stage where I can start working on the actual business logic.

RailsBooster is an attempt to put together all the common configurations, gems and best practices in one place which will eliminate the need of all prerequisites and immediately enables working on the actual business logic.

## 📦 What's in the box? _(work in progress)_

- Authentication using Devise with pretty Login/Sign Up pages
- TailwindCSS as UI framework
- Webpacker configured with PurgeCSS
- Vue.js javascript framework for building modern UIs

## 🛠 Getting Started

- Clone this repo with `git clone git@github.com:BilalBudhani/RailsBooster.git [YOUR PROJECT FOLDER NAME]`
- Run `bundle install && yarn install`
- Run `rails g rename:into [ProjectName]`
- Remove `rename` gem from `Gemfile`
- RailsBooster ships with `Procfile.dev` to run multiple processes with a single command. I recommend installing [Overmind](https://github.com/DarthSim/overmind) or [Foreman](https://github.com/ddollar/foreman) to run this project.
- Start Rails and Webpacker server with `overmind s`

## License

RailsBooster is licensed under the MIT license. (opensource.org/licenses/MIT)
