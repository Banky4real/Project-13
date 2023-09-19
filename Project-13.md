## **Documentation for Project 13**

### Introducing Dynamic Assignment Into Our structure

### Creating another Branch named dynamic-assignments under our ansible-config-mgt repo on github

`git checkout -b dynamic-assignments`

![ansible-config-artifacts-directory-created](./Images/dynamic-assignments-branch-created.png)

### New Layout

![new-layout](./Images/new-layout.png)

### Updating site.yml with dynamic assignments

![updating-site-yml-with-dynamic-assignments](./Images/updating-site-yml-with-dynamic-assignments.png)

### New role created by geerlingguy installed using ansible-galaxy and folder renamed to mysql

`ansible-galaxy install geerlingguy.mysql`
`mv geerlingguy.mysql/ mysql`

![new-role-created-using-ansible-galaxy](./Images/new-role-created-by-geerlingguy-installed-using-ansiblegalaxy-and-renamed-to-mysql.png)

### Uploading our changes to github roles-feature branch

`git checkout main`
`git pull origin roles-feature`
`git merge roles-feature`
`git commit -m "Commit new role files into GitHub and merging with main"`
`git push`

![uploading-changes-to-git](./Images/uploading-changes-to-git.png)

![uploading-changes-to-git](./Images/uploading-changes-to-git-2.png)

### Running our playbook against to configure apache Load Balancer

![Running-our-playbook-and-setting-apacheLB-to-true](./Images/Running-our-playbook-and-setting-apacheLB-to-true.png)

![Running-our-playbook-and-setting-apacheLB-to-true](./Images/Running-our-playbook-and-setting-apacheLB-to%20true-pt2.png)