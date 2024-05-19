
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
![ss1](https://github.com/Chikku-bhat/Dev_rev/assets/73264973/a9e015df-fe5f-40a9-b6d0-72844e988599)

![ss2](https://github.com/Chikku-bhat/Dev_rev/assets/73264973/47f36294-b07e-46ef-8c7b-e45810e26937)
