This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn install `

After all the packages are installed you can run

### `yarn start `

Runs the app in the development mode.<br />
The page will reload if you make edits.<br />

## Important takeaways

### Prevent wasted renderings issues

* For class components

     * convert them into PureComponents ( compare **AddButton.js** file of branch **m3.lesson.1.start** with **master**  )

     * Use **shouldComponentUpdate** when necessary.
 
 
* For functional components

     * Use **useCallBack()** hook to generate a function that only changes when you pass different things in its array of dependencies ( compare **App.js** file of
      branch **master** with **m4.lesson.2.start**  )

     * Convert them into **memoized function** by using **React.memo** ( check **AddButton.js** file of branch **m4.lesson.1.start**  ) 

## Fixing Large Bundles and Expensive Operation Issues

* Caching expensive operation results by using **useMemo()** hook.

* Reduce bundle size by building **production** build whenever you are sending your code to **production**.

* Lazy load components by using **lazy** and **suspense** hook.

