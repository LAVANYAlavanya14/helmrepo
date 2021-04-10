# helmrepo
All helm charts are stored in this repository
First clone this repo in to the server
git clone 

Next step
move the helmchart tar file to this helmrepo folder
mv helchart.tgz helmrepo/

Next step
create a index.yaml file - so it has chart name and all the details required
by using this cmd
$helm repo index helmrepo --url <githubpageurl of this repo>

Next step
Move to the helmrepo directory to commit
$cd helmrepo   # which is the repo name of this 

Next step
After creating index.yaml file now move files to working area to staging area
$git add .

Next step
After that commit the files with commit message
$git commit -m "Added to the helmrepo a chart"

Next step
Push the files to this repo
git push

Now we can see our helmchart tar files in our github helmrepo
