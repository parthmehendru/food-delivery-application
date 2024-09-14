# Parcel
- Dev Build
- Local Server
- HMR = Hot Module Replacement
- File Watching algorithm - written in C++
- Faster Builds due to Caching
- Image optimization
- Minification 
- Bundling
- Compressing(removing whitespaces)
- Consistent Hashing
- Code Splitting
- Differential Bundling - support older browsers
- Diagnostics
- Error Handling
- HTTPs
- Tree Shaking Algorithm - remove unused code
- Different dev and prod bundles

# Redux Toolkit
 - Install @reduxjs/toolkit and react-redux
 - Build our store
 - Connect our store to our app
 - Slice (cartSlice)
 - dispatch(action)
 - Selector (reading the data with useSelector and the component is  automatically subscribed to the store. )

# Types of testing (developer)
 - Unit Testing
 - Integration Testing
 - End to End Testing - e2e testing

# Setting up Testing
 - Install React Testing Library
 - Install jest
 - Install babel dependencies
 - Configure Babel
 - Configure Parcel Config file to disable default babel transpilation
 - Jest configuration - npx jest --init
 - Install jsdom library
 - Install @babel/preset-react - to make JSX work in test cases
 - Include @babel/preset-react inside my babel config
 - Install @testing-library/jest-dom