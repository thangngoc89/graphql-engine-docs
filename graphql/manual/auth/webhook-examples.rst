Auth Webhook Examples
=====================

We've put together a github nodejs repo that has some auth webhook examples configured.

- `View on github <https://github.com/hasura/sample-auth-webhook/blob/master/server.js#L25>`__
- Deploy with `glitch <https://glitch.com/>`__.

  .. image:: https://raw.githubusercontent.com/hasura/sample-auth-webhook/master/assets/deploy-glitch.png
    :width: 200px
    :alt: deploy_auth_webhook_with_glitch
    :class: no-shadow
    :target: http://glitch.com/edit/#!/import/github/hasura/sample-auth-webhook

Once deployed, you can use any of the following endpoints as your auth webhook in the GraphQL engine:

- ``/simple/webhook``   (`View source <https://github.com/hasura/sample-auth-webhook/blob/master/server.js#L25>`__)
- ``/auth0/webhook``    (`View source <https://github.com/hasura/sample-auth-webhook/tree/master/firebase>`__)
- ``/firebase/webhook`` (`View source <https://github.com/hasura/sample-auth-webhook/tree/master/auth0>`__)

.. note::

    If you are using ``auth0`` or ``firebase`` you will have to set the associated environment variables.
