## Introduction

This documentation aims to ensure that our components function according to CRUD and reliably in our Ascending Notes application. Users will also have the ability to star their notes to mark its importance and also delete notes.

Our target audience are fellow students, developers, QA engineers who are interested in using and testing our notes application. 

Unit tests are essential and play a crucial role in the overall testing strategy by focusing on individual units or components of a software system. Unit tests for React components are there to help catch bugs early in the development process and ensure that each component behaves as expected. Testing is necessary for the following reasons: bug detection and prevention, enhanced user experience, increased confidence in releases, cost savings, maintaining business reputation, adaptability and scalability, and regulatory compliance.Ω

## Test Environment Set Up

Dependencies:

      "devDependencies": {
        "@babel/preset-env": "^7.23.9",
        "@babel/preset-react": "^7.23.3",
        "@testing-library/jest-dom": "^6.4.1",
        "@testing-library/react": "^14.2.1",
        "@testing-library/user-event": "^14.5.2",
        "@types/react": "^18.2.43",
        "@types/react-dom": "^18.2.17",
        "@vitejs/plugin-react": "^4.2.1",
        "eslint": "^8.55.0",
        "eslint-plugin-react": "^7.33.2",
        "eslint-plugin-react-hooks": "^4.6.0",
        "eslint-plugin-react-refresh": "^0.4.5",
        "jest": "^29.7.0",
        "jest-environment-jsdom": "^29.7.0",
        "postcss": "^8.4.33",
        "postcss-preset-mantine": "^1.12.3",
        "postcss-simple-vars": "^7.0.1",
        "vite": "^5.0.8"
      }

More information regarding how to configure Jest (https://jestjs.io/docs/configuration) and React Testing Library can be found on the official documentation website. 

#Test File Structure

Our files are organized according to components. Each component has its own file and the respective test in the same folder.







