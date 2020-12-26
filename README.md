# 🚀 RailsBooster

Pre-Configured Ruby On Rails Boilerplate To Provide Instant Productivity ⚡️

## 🤓 Motivation behind the project

I regularly keep experimenting with ideas and problems to solve with Ruby On Rails as my choice of stack. However, I find myself configuring Rails as per my preference with every new project to reach to a stage where I can start working on the actual business logic.

RailsBooster is an attempt to put together all the common configurations, gems and best practices in one place which will eliminate the need of all prerequisites and immediately enables working on the actual business logic.

## 📦 What's in the box?

- I prefer using [Vue](https://vuejs.com) and [Inertia](https://inertiajs.com) instead of Turbolinks.
- Authentication using Devise with pretty Login/Sign Up pages
- TailwindCSS as CSS framework with PurgeCSS configured
- DotEnv support for picking up variables from `.env` only for development & testing environment
- [SuckerPunch](https://github.com/brandonhilkert/sucker_punch) for running lightweight async background jobs as `ActiveJob` default adapter
- Uses [Standard](https://github.com/testdouble/standard) as Ruby linter
- View outgoing emails at [/letters](http://localhost:3000/letters) in development
- Model annotations to ease decision making

## 🛠 How to use

- Clone this repo with `git clone git@github.com:BilalBudhani/RailsBooster.git [YOUR PROJECT FOLDER NAME]`
- Run `bundle install && yarn install`
- Run `cp .env.example .env`
- Use your IDE's find & replace functionality to rename `RailsBooster` to `[ProjectName]`
- RailsBooster ships with `Procfile.dev` to run multiple processes with a single command. I recommend installing [Overmind](https://github.com/DarthSim/overmind) or [Foreman](https://github.com/ddollar/foreman) to run this project.
- Start Rails and Webpacker server with `overmind s`

### 👀 Roadmap
- [x] Basic authentication
- [x] Configure TailwindCSS to provide basic styling
- [x] Use production ready backgrounding gem for async usage
- [x] Setup a linter for keeping styleguide & formatting in check
- [ ] Template for mailer views
- [ ] Sign in via Google authentication
- [ ] Move to [clearance](https://github.com/thoughtbot/clearance) for simpler authentication abstraction
- [ ] ActionCable support
- [ ] ActiveStorage support
- [ ] Github actions to enforce linters

## License

RailsBooster is licensed under the MIT license. (opensource.org/licenses/MIT)
