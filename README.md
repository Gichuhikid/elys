APIRequestContext is used to create a context for making API requests. This context is created in the beforeAll hook and disposed of in the afterAll hook.
The requestContext is used to make get, post, put, and delete requests.
The baseURL is set when creating the requestContext, so only the endpoint paths are needed in the request methods.
This approach ensures that the post, put, delete, and other HTTP methods are correctly recognized and available on the APIRequestContext object.








