# Creating a Kubernetes Cluster on DigitalOcean with Python and Fabric

Check out the [blog post](https://testdriven.io/creating-a-kubernetes-cluster-on-digitalocean).

## Want to use this project?

1. Fork/Clone

1. Create and activate a virtualenv

1. Install the requirements

1. [Sign up](https://m.do.co/c/d8f211a4b4c2) for Digital Ocean and [generate](https://www.digitalocean.com/docs/apis-clis/api/) an access token

1. Add the token to your environment:

    ```sh
    $ export DIGITAL_OCEAN_ACCESS_TOKEN=[your_token]
    ```

1. [Add](https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/to-account/) a public SSH key to your account.

1. Spin up the cluster:

    ```sh
    $ sh create.sh
    ```
