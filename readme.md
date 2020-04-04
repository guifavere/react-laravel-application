<h1 align="center">
  <strong>Laravel to-do list app with react</strong>
</h1>

Laravel application with react. Example taken from [pushers's post](https://blog.pusher.com/react-laravel-application).

<img alt="React Laravel Application" src="https://i.imgur.com/5JEmfDe.png" title="React Laravel Application" />

## Installation

1. Clone the repo using: `git clone https://github.com/GuilhermeFavere/react-laravel-application.git`.
2. Move to the appropriate directory: `react-laravel-application`.
3. Install the dependencies with `composer install`, and `npm install`.
4. Run `npm run dev` to generate the assets.
5. Copy the `.env.example` to `.env`, and fill the values of your environment (this project was deployed on Heroku, so if you want to use a different database host than the: "Heroku postgres", you must update the file: "config/database.php" with your database config).
6. Finally run `php artisan key:generate` to generate the app key.

Now the app is ready for use, you can open it running: `php artisan serve` in the root of the project directory. You also can check it <a href="https://react-laravel-application.herokuapp.com/" target="_blank" title="Project deployed on Heroky">here</a>.
