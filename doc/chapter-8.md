# Tree table for nested set

`EasyAdminPlus` provides a nested set viewer.

<p align="center">
    <img src="images/tree.png" align="center" alt="Tree list viewer" />
</p>

-------
### How to use it

Configure the nested set entity with tree: true :
```yaml
easy_admin:
    entities:
        Service:
            class: App\Entity\Service
            tree: true
            disabled_actions: []
            list:
```

-------
### Dependency

EasyAdminPlus tree mode need only 3 field. lft, rgt and id.
We don't need to be a gedmo nestedset Entity. But it is of course possible.

Thanks to http://ludo.cubicphuse.nl/jquery-treetable for the javascript part.

This plugin include the treetable, you don't need to include it.

-------
[Back to main readme](../README.md)
