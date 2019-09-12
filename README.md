# Touchpoints Site
## A customer service tool for federal agencies that helps them improve the quality of service they deliver to their customers

Touchpoints is a product of the Technology Transformation Services, and maintained by the Office of Products and Programs in the General Services Administration.


- [Product documentation](https://github.com/GSA/touchpoints/tree/master/docs)
- [How to use Touchpoints]( https://github.com/gsa/touchpoints/wiki)


---

## How this application is hosted

- **Touchpoints site / touchpoints.digital.gov**<br/>A Federalist site with all documentation and support material about the Touchpoints app. This is where we’ll direct people who are interested in knowing more about using Touchpoints or how to sign up. It will also direct people to log-in to the Touchpoints app.

- **Touchpoints App / app.touchpoints.digital.gov**<br/>This a the RAILs application on Cloud.gov, and is the main source of the functionality.

---

## How to install locally

After cloning the repo, navigate to the correct folder and install USWDS, Jekyll, and any necessary dependencies using:
```
npm start
```
Then, to run the site locally:
```
npm run serve
```
If all goes well, visit the site at http://localhost:4000.

USWDS assets are in `assets/uswds/fonts` and `assets/uswds/img`.

SASS files are kept in the `/_sass` directory. To watch for changes and recompile the styles, run:
```
npm run watch
```
