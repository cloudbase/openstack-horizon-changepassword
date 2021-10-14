==================================================================
Change Instance Password Feature for Horizon (OpenStack Dashboard)
==================================================================

Applying this patch to Horizon adds an option to the instance action dropdown which allows you to change its password.

The option ("Change Password") is shown if the instance is shutdown or in an active state.

You can enable password changing through `OPENSTACK_ENABLE_PASSWORD_CHANGE` setting. It is enabled by default.
