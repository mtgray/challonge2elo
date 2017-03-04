challonge2elo
=============

challonge2elo is a tool to calculate `Elo ratings <https://en.wikipedia.org/wiki/Elo_rating_system>`_ from `Challonge tournaments <http://challonge.com/>`_. Ratings are output to a CSV file, and they are also saved in a JSON file so that you can go back and update them later with future tournaments.

Note that this tool relies on players having the same names for each tournament. If you are a tournament organizer, make sure your naming scheme is consistent!

Installation
------------

Install via pip:

.. code-block:: bash

    $ pip install challonge2elo

Log in to your Challonge account and `get your API key <https://challonge.com/settings/developer>`_. Then export your username and API key as environment variables:

.. code-block:: bash

    export CHALLONGE_USERNAME=username
    export CHALLONGE_API_KEY=key

Example Usage
-------------

Create ratings by passing in a few tournament IDs:

.. code-block:: bash

    $ challonge2elo ggsmash-116_smash4 ggsmash-416_smash4
