- All development front-controllers (app_dev.php etc.) removed during the deployment process and denied by the web server
- Application is working correctly through https
- E-mail addresses and credentials changed to production values
- Cron scripts installed (if applicable)
- Correctly configured shared files directories (we use Capistrano)
- Confidential data like JWT Tokens, Security Tokens, API keys changed and not stored in repository
- All assets minimized and compressed
- RWD tests on Browserstack passed
- OWASP top 10 tests passed
- php.ini settings updated: time zone, max upload size etc.
- Unnecessary Symfony bundles disabled
- Custom 404 and 500 error pages
- Custom favicon
- Initial database migration added
- Sentry/error tracking configured

Feel free to contribute!

More info: https://blog.accesto.com/blog/2017/07/25/project-release-checklist/
