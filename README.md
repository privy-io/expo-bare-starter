# Privy Expo Starter (bare)

This demonstrates a minimal working installation of the privy sdk in an
[bare](https://docs.expo.dev/bare/overview/) expo app.

## Setup

1. Install dependencies

   ```sh
   npm i
   ```

1. Add your Privy app ID in `App.js`

   ```jsx
   export default function App() {
     return (
       <PrivyProvider appId="<your-privy-app-id>">
         <View style={styles.container}>
           <Content />
         </View>
       </PrivyProvider>
     );
   }
   ```

## Run the app

```sh
# ios
npm run ios

# android
npm run android
```
