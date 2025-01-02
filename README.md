1、 pnpm vite  build
2、 Check the build results of the index file in the dist directory, which was not processed with babel-plugin-react-compiler.

3、Remove autoCodeSplitting from the Vite configuration and check the build structure again; this has an effect.
4、Or change the order of the @tanstack/router-plugin/vite plugin and the React plugin, and it will still work fine.
