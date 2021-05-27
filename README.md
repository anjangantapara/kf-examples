# kf-examples
Playing with kf-examples
command to run knative.yaml:
    kubectl appy -f knative.yaml
Command to run the kf-serving example
    kubectl apply -f kf-serving-sklearn-eample.yaml
command to score the model
curl -v -H "Cookie: authservice_session=MTYyMDU2MDMyNXxOd3dBTkZWV1dVaElXRFpMVmtVMVRrWlROa2RhUkVWR1YxZENRVmRMVlZOS1IwVlNSMWxQUWtoUVdqZFVRamRFVTFaWlZWZFNXVUU9fA4iuWyR-oEV3LF3x12JClM_H4CVNgSq-6r-fyzI-jJI; _xsrf=2|22d4cc5a|8ce972079d5f074fb3b2b1b5cad7fd5c|1619095342" http://sklearn-iris-predictor-default.anjan.platform.xcc-dev.com/v1/models/sklearn-iris:predict -d @./iris-input.json
