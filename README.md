# kf-examples
Playing with kf-examples
command to run knative.yaml:
    kubectl appy -f knative.yaml
Command to run the kf-serving example
    kubectl apply -f kf-serving-sklearn-eample.yaml
curl -v -H "Cookie: authservice_session=MTYyMDM2OTcxM3xOd3dBTkZOWFJVNUVOVFZMVWxVM1ZrVlJVMXBZVWxNeU5GRktSMFpaUmpkT1VGQlBOa016V1VGU1VUVkZURmRJV1VoVU5WaEJTVUU9fL8zuL1HxCLEcfGi-DDX9BmlD2jr6xlD7omUYnbh0EnH; _xsrf=2|22d4cc5a|8ce972079d5f074fb3b2b1b5cad7fd5c|1619095342" http://kf-serving-sklearn-example.anjan.platform.xcc-dev.com/v1/models/sklearn-iris:predict -d @./iris-input.json
