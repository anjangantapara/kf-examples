# kf-examples
Playing with kf-examples
command to run knative.yaml:
    kubectl appy -f knative.yaml
Command to run the kf-serving example
    kubectl apply -f kf-serving-sklearn-eample.yaml
command to score the model
curl -v -H "Cookie: authservice_session=; _xsrf=" http://kf-serving-sklearn-example.anjan.platform.xcc-dev.com/v1/models/sklearn-iris:predict -d @./iris-input.json
