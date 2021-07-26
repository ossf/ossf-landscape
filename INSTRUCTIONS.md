# Instructions for using this template

This template is designed to help you get started on building a landscape. It's based on the TODO Group OSPO landscape.

- Clone this template repo into your github organization or account.
- Create the subdomain for the landscape ( typically landscape.yourprojectdomain ) and a short domain that will forward to this ( typically l.yourprojectdomain )
- Create the landscape logo and replace [images/left-logo.svg](images/left-logo.svg)
- Set [images/right-logo.svg](images/right-logo.svg) as your project's logo
- [Generate](https://www.qrcode-monkey.com) a QR code, setting colors to black. Save as SVG and overwrite [images/qr.svg](images/qr.svg).
- If you're working with the LF, give admin privileges to the new repo to jmertic and write privleges to AndreyKozlov1984, jordinl83, and CNCF-Bot and ping John after creating an account at slack.cncf.io. Alex Contini and John are available there to help you recreate SVGs based on a PNG of the company's logo, if necessary, and to fix other problems.
- Set the repo to only support squash commits and turn off DCO support, since it doesn't work well with the GitHub web interface.
- Update [config.yaml] and [settings.yaml] using the instructions in each file
- Do the pre-requisites at https://github.com/jmertic/landscape-tools/blob/master/INSTRUCTIONS.md#recommended---automatic-build-with-github-actions.
- Go to 'Actions' in the top menu. You should see a job called 'Update members' on the right side under 'Workflows'. Click that, then on the next screen click 'Run workflow'. This will build out the landscape with just your members.
- If it all works, you should have your first landscape built with just members of your project, and ready to start your landscape journey!
