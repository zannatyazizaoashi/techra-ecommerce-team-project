# TechRA

TechRA is a team e-commerce project with a PC builder, 3D interface, and AI-based recommendations. This repository is a cleaned portfolio snapshot of the [original team repository](https://github.com/rahat239/CSE470-TechRA), kept private while it is prepared for a CV.

## My contribution

Zannaty Aziza (`zannatyazizaoashi`) contributed to the shared project. Her commits in the original Git history include work on the user controller, products, cart, brands, profile, and frontend validation helper. See the original repository for the full commit history and each contributor's work.

Other contributors recorded in the original history include Rahat Ahmed (`rahat239`), Mosaiba, and `MohammadAbdullah999`. TechRA is a team project, even though this portfolio copy is hosted under Zannaty's account.

## Stack and structure

- `client/`: React and Vite frontend, including the PC builder interface.
- `src/`: Express API, MongoDB models, and backend services.
- `ml/`: Python training code, data, and recommendation models.
- `app.js` and `index.js`: backend entry points.

## Local setup

1. Use Node.js 18 or newer and a MongoDB database.
2. Set `MONGODB_URI` and `JWT_SECRET` in the shell or hosting environment before starting the backend.
3. Set `SMTP_USER` and `SMTP_APP_PASSWORD` if you want email features. Set `ADMIN_EMAIL` only for an account that should receive the admin role.
4. Run `npm install` in this directory. The package's post-install script installs and builds the React client.
5. Run `npm start` and open the local server shown in the console.

Keep real credentials outside Git. The original source had hardcoded credentials; this copy uses environment variables. Credentials from the original project should be rotated by the account owners.

## Snapshot notes

The original Git history, dependency folders, generated builds, IDE files, and `dummy-data/` are not copied here. This snapshot has not been tested end to end with live services. The original team repository remains the record of authorship and project history.
