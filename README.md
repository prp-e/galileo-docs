# Galileo (Mann-E's B2B Service) Documents

<p align="center">
    <img src="galileo-pic.png" width=256 height=256 />
</p>

## Examples

## API Docs

### Acquiring the token

To acquire a token, send an email to us at _haghiri75@gmail.com_ and we'll reach out to you as soon as possible with a proposal and also the more detailed guide. Although we tried to make this part of the docs a very neat and understandable document for everyone, but we also may provide support for our B2B customers.

### Verify the token 

__ENDPOINT__ : `/verify_token`
__METHOD__ : `POST`

Using a _curl_ command like this, you can verify that your token is valid or not. 

```bash
curl -X POST -k -H 'Content-Type: application/json' -i 'https://galileo.manne.ir/verify_token' --data '{
 "token": "manne-YOUR_TOKEN"
}'
``` 

The response from the server will be like this:

```json
{
  "message": "Your token is valid",
  "name": "Mann-E"
}
```


### Creating an image

__ENDPOINT__ : `/images`
__METHOD__: `POST`

### Listing all the images of your token

### Getting a single image

## Help and Support