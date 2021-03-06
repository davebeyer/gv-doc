# Membership Sub-groups

Sub-groups provide additional flexibility in how you manage your
membership and target your emails.  Sub-groups can have:

* Can have their own Admins and Editors
* Can be moderated or not
* Can have their own set of lists
* Multiple sub-group levels are possible, members of a sub-group are
  automatically a member of the parent (grand-parent, ..) groups.

<span class="support"> 
Remember that group membership applies "upward" from that group's
sub-groups (or sub-sub-groups).  So a group Member (or Editor or
Admin) in a child sub-group will automatically be a Member in the
current group.

For example, if you're an Editor of the "classclowns" sub-group of the
"2ndgrade" group in the "central valley" account, then you'll be at
least a Member of the "2ndgrade".
</span>

<span class="adv">  <!-- START ADVANCED -->

Additions, modifications, and deletions of new or existing sub-groups
can also be performed by emailing instructions to your account server; 
[see here](./emailactions?gv-qargs=0) for instructions.


</span>  <!-- END ADVANCED -->



## Example

For example, for a main group account named "lighthouselabs", you might
have sub-groups named "team", "advisors", and "investors".  Emails to
the team could be easily targetted using the address:

```
team.lighthouselabs@groupvine.com
```

It may also make sense to further classify your Lighouse Labs community
members using Lists to identify some of their interests, such as
"golfers" and "musiclovers".  You could then send an email to all the
musiclovers using the address:

```
musiclovers~~lighthouselabs@groupvine.com
```

Or, if you only want to send it to music-loving advisors, use:

```
musiclovers~~advisors.lighthouselabs@groupvine.com
```

Don't worry, you can always use the address helper on the site.

<span class="adv">
Note that role privileges apply "downward." So an
Administrator at the account level will have Admin privileges
throughtout all sub-groups in the account, or an Administrator of a
"2ndgrade" sub-group also have Admin privileges in its "classclowns"
sub-group.   

However, one sidenote is that only Administrators that are explicit
Admins for that specific group are are listed under the "group:"
columns of membership Exports, and only explicit group Admins receive
the group's moderation request emails.
</span>
