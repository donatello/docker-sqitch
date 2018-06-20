docker-sqitch
-------------

# run

    docker run --rm donatello/sqitch:pgsql

# build

    docker build -t donatello/sqitch:base .
    docker build -t donatello/sqitch:pgsql pgsql
    docker build -t donatello/sqitch:mysql mysql
