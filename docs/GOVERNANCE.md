# Decision making in the curl project

A rough guide to how we make decisions and who does what.

## BDFL

This project was started by and has to some extent been pushed forward over
the years with Daniel Stenberg as the driving force. It matches a standard
BDFL (Benevolent Dictator For Life) style project.

This setup has been used due to convenience and the fact that is has worked
fine this far. It is not because someone thinks of it as a superior project
leadership model. It will also only continue working as long as Daniel manages
to listen in to what the project and the general user population wants and
expects from us.

## Legal entity

There is no legal entity. The curl project is just a bunch of people scattered
around the globe with the common goal to produce source code that creates
great products.

The copyrights in the project are owned by the individuals and organizations
that wrote those parts of the code.

## Decisions

The curl project is not a democracy, but everyone is entitled to state their
opinion and may argue for their sake within the community.

All and any changes that have been done or will be done are eligible to bring
up for discussion, to object to or to praise. Ideally, we find consensus for
the appropriate way forward in any given situation or challenge.

If there is no obvious consensus, a maintainer who's knowledgeable in the
specific area will take an "executive" decision that they think is the right
for the project.

## Key roles

### Maintainers

A maintainer in the curl project is an individual who has been given
permissions to push commits to one of the git repositories.

Maintainers are free to push commits to the repositories at their own will.
Maintainers are however expected to listen to feedback from users and any
change that is non-trivial in size or nature *should* be brought to the
project as a PR to allow others to comment/object before merge.

### Former maintainers

A maintainer who stops being active in the project will at some point get
their push permissions removed. We do this for security reasons but also to
make sure that we always have the list of maintainers as "the team that push
stuff to curl".

Getting push permissions removed is not a punishment. Everyone who ever worked
on maintaining curl is considered a hero, for all time hereafter.

### Security team members

We have a security team. That's the team of people who are subscribed to the
curl-security mailing list; the receivers of security reports from users and
developers. This list of people will vary over time but should be skilled
developers familiar with the curl project.

The security team works best when it consists of a small set of active
persons. We invite new members when the team seems to need it, and we also
expect to retire security team members as they "drift off" from the project or
just find themselves unable to perform their duties there.

### Server admins

We run a web server, a mailing list and more on the curl project's primary
server. That physical machine is owned and run by Haxx. Daniel is the primary
admin of all things curl related server stuff, but Björn Stenberg and Linus
Feltzing serve as backup admins for when Daniel is gone or unable.

The primary server is paid for by Haxx. The machine is physically located in a
server bunker in Stockholm Sweden, operated by the company Portlane.

The web site contents are served to the web via Fastly and Daniel is the
primary curl contact with Fastly.

### BDFL

That's Daniel.