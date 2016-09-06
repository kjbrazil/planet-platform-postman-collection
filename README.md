# Planet Platform Postman Collection (v0 & v1)

A set of example HTTP requests for the v0 and v1 Planet APIs using Postman. These include:

* Catalog (v1)
* Scenes (v0)
* Orders (v0)
* Areas of Interest (v0)

# Requirements

In order to utilize this repo you will need two things:

1. A [Planet Platform account](https://www.planet.com/markets/explorer-signup/).
2. [Postman](https://www.getpostman.com) for Mac or Chrome.

# Setup

1. Clone or download this repo to your local machine.
2. Open Postman.
3. In the top left corner click "Import".
4. Click "Import Folder".
5. Drag or find your ``planet-platform-postman-collection`` folder and click open.
6. Both the collection and the environment variables will be imported to Postman.
7. In the top right corner to the left of the eye icon, click the drop down and select "Manage Environments".
8. Click "Planet".
9. Navigate to your [Planet Platform apps page](https://www.planet.com/apps/) to obtain your key.
10. Navigate back to Postman and replace ``your-api-key`` with your actual credentials.
11. Click "Update" and close the window.
12. Click the environment drop down again and select "Planet".
13. You are now ready to start making API calls!
14. Try querying all Planet Dove scenes by clicking the Scenes folder > "Query All Planet Dove Scenes" > Send.

# Support

If you encounter any issues please [create an issue](https://github.com/kjbrazil/planet-platform-postman-collection/issues/new). Please also feel free to improve upon the collection and submit pull requests. :-)
