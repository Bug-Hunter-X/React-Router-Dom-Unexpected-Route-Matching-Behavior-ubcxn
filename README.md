# React Router Dom Route Matching Issue

This repository demonstrates an unexpected behavior in React Router Dom v6 when dealing with nested routes and a wildcard route (`*`). The wildcard route is intended to catch any unmatched paths, but it's not working as expected.  The issue is related to how routes are matched and the order they are defined.  The solution involves adjusting the route order to ensure the wildcard route is correctly handling unmatched paths.