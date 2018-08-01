# aws-ecs-util

go utility tool for aws ecs (gofe)

## description

* show desired,pending,running ecs tasks in all/specific cluster/services
* detect desired > running ecs tasks in all/specific cluster/services
* show service events in all/specific cluster
* post to slack

## install

TODO

## usage

```
# show desired,pending,running ecs tasks in all clusters
gofe -c show-tasks -a

# detect desired > running ecs tasks in all clusters (detect errors)
gofe -c show-tasks -a -e

# filter cluster-name with sc option
gofe -c show-tasks -cn cluster-name

# filter service-name with ss option
gofe -c show-tasks -sn service-name

# show service events
gofe -c show-events

```

### ref

* https://deeeet.com/writing/2014/08/27/cli-reference/
* http://yapcasia.org/2014/talk/show/b49cc53a-027b-11e4-9357-07b16aeab6a4
* https://www.gnu.org/prep/standards/html_node/Option-Table.html#Option-Table

