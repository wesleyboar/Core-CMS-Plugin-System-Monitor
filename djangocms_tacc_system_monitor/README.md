# Developer Notes

This is a _minimal_ conversion of the Frontera Sysmon snippet to a Django CMS plugin.

> There is a functionally more advanced plugin, [bitbucket:taccaci/tacc-system-monitor](https://bitbucket.org/taccaci/tacc-system-monitor), which allows:
>
> - server-side requests (Python) instead of client-side requests (JavaScript)
> - multi-system tables

## To Do

- https://github.com/TACC/Core-CMS/issues/295:
    - multiple systems
    - server-side support
- Remove assumption of existing styles for certain classes:
    - [`iconworks`](https://icon-works.com/)
    - [`badge`](https://getbootstrap.com/docs/4.0/components/badge/)
