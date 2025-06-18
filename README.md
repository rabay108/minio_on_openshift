# minio_on_openshift
oc new-project minio
oc apply -f minio-secret.yaml
oc apply -f minio-pvc.yaml
oc apply -f minio-service.yaml
oc apply -f minio-api.yaml
oc apply -f minio-ui.yaml
