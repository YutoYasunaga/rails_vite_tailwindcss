# Ruby on Rails with Vite, Tailwind CSS Starter Kit

This repository provides a base Rails application with Vite for faster frontend tooling, and Tailwind CSS for utility-first CSS styling. It's also configured with rubocop, rails_best_practices, and brakeman to ensure your code remains clean and secure.

## Prerequisites
- Ruby 3.x
- Rails 7.x
- Tailwind 3.x
- Node.js 20.x
- Yarn 1.x
 
## Getting Started

### 1. Clone the repository

```
git clone https://github.com/YutoYasunaga/rails_vite_tailwindcss.git
```

```
cd rails_vite_tailwindcss
```

### 2. Install dependencies

```
bundle install && yarn install
```

### 3. Start the Rails server and Vite

This command will run both the Rails server and Vite for frontend development:

``` 
bin/dev
```

By default, the server will start at http://localhost:3000.

## Development Tools

### RuboCop

Run RuboCop to ensure your Ruby code conforms to the style guide:

```
bundle exec rubocop
```

If you want to automatically correct offenses:

```
bundle exec rubocop -A
```

### Rails Best Practices
Analyze your Rails projects with rails_best_practices:

```
bundle exec rails_best_practices .
```

### Brakeman
Brakeman is a static analysis security vulnerability scanner for Ruby on Rails applications:

``` 
bundle exec brakeman
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
