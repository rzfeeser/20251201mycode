ansible --version
# find the version of python supporting ansible

python3 --version # maybe python --version
# confirm this version of python is supporting ansible

# find requirements.txt file from ansible collection repo
# recreate in your environment

# use the confirmed version of python to install python dependencies
# from requirements.txt
python3 -m pip install -r requirements.txt

# next, find any module ending _facts or _info <- these are all READ ONLY
# get any of these to work / register the results / debug facts out
# none of this will be impactful to production or your VMware stack

