# Explorer Github (Technical Test AdaKerja)

## Task

The goal is to create a React Native application which we will be able to run on both

Android and iOS. The application should:
1. Display a login screen where user can enter their Github login and a button linking to the
next screen

2. Display a password screen where user can enter his Github password and a submit button

3. After successful login, the app should display a screen with a single text input field, where
user can enter repository name (with default being facebook/react-native ) and a submit
button

4. The last screen (after submitting repository name) should display a scrollable list of
commits to this repository similar (data-wise) to https://github.com/facebook/react-native/commits/master, including at least: 
    - committer's avatar, 
    - committer's username, 
    - commit

    message and information about when the commit has been done

5. User should be able to go back and browse another repository

6. Display a Logout button on every page where the user is authenticated. The user should
not be able to go back to the auth screen with anything else than this button

7. Bonus points for list pagination, but fetching only last N commits is also acceptable. If you
can't manage to implement pagination, but you have an idea - please provide a TODO
comment or write it down in the Readme
For navigation, use a solution of your choice. Please remember about error handling, for
example for API calls.

## Library 

- React Navigation
- Axios
- Redux
- Redux Thunk
- Redux Logger