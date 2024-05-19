
# DevRev Assignment



## Utilizing DevRev API
For using a DevRev api we should have a DevRev Account.

Once we create a DevRev account the next important step is to Generate a PAT(Personal Access Token) 

Here using the generated PAT the DevRev API can be accessed and a work item can be created
URL to create a work item(issue) is

    https://api.devrev.ai/works.create

 Header and data format is given below

       curl -X POST https://api.devrev.ai/works.create \
        -H "Authorization: <apiKey>" \
        -H "Content-Type: application/json" \
        -d '{
     "type": "issue",
     "applies_to_part": "string",
     "owned_by": [
       "string"
     ],
     "title": "string"
    }'

## Output of Creating a work item using DevRev Api

![ss1](https://github.com/Chikku-bhat/Dev_rev_api_assignment/assets/73264973/0c7feb16-95c5-4a13-ad91-475f8daf9a02)

![ss2](https://github.com/Chikku-bhat/Dev_rev_api_assignment/assets/73264973/77f1f955-89e0-4e27-b96c-1a29fc425006)


