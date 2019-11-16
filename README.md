# ElasticSearchInstallation
    - Added mapping or for data
    ``PUT /bigmarketdata
        {
        "mappings": {
            "marketData":{
            "properties": {
            "Item_Identifier": {
            "type" : "keyword"
            },
            "Item_Weight": {
                "type" : "float"
            },
            "Item_Fat_Content": {
                "type": "keyword"
            },
            "Item_Visibility": {
                "type": "float"
            },
            "Item_Type": {
                "type": "float"
            },
            "Item_MRP": {
                "type": "float"
            },
            "Outlet_Identifier": {
                "type": "keyword"
            },
            "Outlet_Establishment_Year": {
                "type": "integer"
            },
            "Outlet_Size": {
                "type": "keyword"
            },
            "Outlet_Location_Type": {
                "type": "keyword"
            },
            "Outlet_Type": {
                "type": "keyword"
            },
            "Item_Outlet_Sales": {
                "type": "float"
            } 
            }
            }
        }
        }``
## GIT BASIC 
    - git add filename "Add the file locally"
    - git commit -m "message" "After adding file commit the change with a message"
    - git push origin master "Add those changes to master or to any other branch/ Replace master with your branch name"
    - git checkout -b branchname "Create a new branch with given branch name"
    - git config --global user.name "Check the git global name config on your system"
    - git config --global user.email "Check the git global email config on your system"
    - git remote add origin https://github.com/PalakGoyal20/ElasticSearchInstallation.git "Adding a remote URL to your repo"
    - git remote -v "Check for the remote url"
    - git remote set-url origin https://github.com/USERNAME/REPOSITORY.git "Set a new remote to existing repo"