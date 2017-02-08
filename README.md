# \<serverless-auth\> with Polymer 2

Authentication for aws serverless apis using aws

```html
<serverless-auth
    id="auth"
    api-endpoint="https://apiid.execute-api.eu-central-1.amazonaws.com/stage"
    google-client-id="294470285834-cu6ubptede4g34le8s7jr43j4hnk3921.apps.googleusercontent.com"
    region="{{_region}}"
    access-key-id="{{_accessKeyId}}"
    secret-key="{{_secretKey}}"
    signed-in="{{signedIn}}"
    loading={{loading}}
    session-token="{{_sessionToken}}"></serverless-auth>
```

```js
this.$.auth.googleSignIn();
```
