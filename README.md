# Demo IPFS contract with Web UI

Edit ipfs priviliges

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin '[\"*\"]'

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods '[\"GET\", "\POST\"]'

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Headers '[\"Authorization\"]'

ipfs config --json API.HTTPHeaders.Access-Control-Expose-Headers '[\"Location\"]'

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials '[\"true\"]
