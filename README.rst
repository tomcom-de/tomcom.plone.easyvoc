Information
===========

This product provide an easy way in Handling key value pairs which should be shown in for
example drop down lists.

First you has to define a key to identify the whole list. For example mycontenttype-mydropdownfield

Than press save.

After you saved, a new link will apear for enter vocabulary valus.

Put every value in a new single line. The entered values will be numbered in ascending order starting by 1.

If you like to rename a value use the rename dropdown below the value list.

If you remove a key from the list, the value will only be hidden in the selection dropdown so the history
will be working for older entries.

You an reactivate the entry by putting it again in the value list.

The following example returns a key,value pair list.

::

    context.getBrowser('easyvoc').get('mycontenttype-mydropdownfield')


The following example returns the value for the key

::

    context.getBrowser('easyvoc').get_value('mycontenttype-mydropdownfield',context.mycontenttype-mydropdownfield)


For getting translations running, enter values in you preffered default language an use po files.

The design is based on a bootstrap 2.3.x layout. Bootstrap is not included

