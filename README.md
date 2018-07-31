# React-Static - Redux Example

This project is to demo https://github.com/nozzle/react-static/issues/652.

1. Run using `yarn build && yarn serve`. (Running with `yarn start` will not reproduce the issue)
2. Go to http://localhost:3000/
3. Click '404' in the header, the path should update to a route that does not exist

Expected: 404 page should render

Actual:
The path is updated but 404 page is not rendered.
Refresh the page and the 404 page is rendered.