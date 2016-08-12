# tictactoe
A sample of Anura's capabilities for making board and card games -- an implementation of Tic-Tac-Toe.

Basic usage:

- Clone into your Anura modules/ directory.
- Run with anura --module=tictactoe

To run your own matchmaking server locally, using a JSON file as the database, you can run this:

    anura --module=tictactoe --db-json-file=tictactoe-db.json --utility=tbs_matchmaking_server

Then connect with your client:

    anura --module=tictactoe --server=localhost:23456
