# openshift-templates

To add the templates global for all projects to use:

git clone https://github.com/pblaas/openshift-templates.git
cd openshift-templates
for i in `dir *.json`; do oc create -f $i -n openshift; done

