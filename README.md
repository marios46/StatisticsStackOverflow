**STATISTICS STACKOVERFLOW** \
**MARIOS TSIGKAS**

**DESCRIPTION** \
_For a given date/time range calculate:_ \
The total number of accepted answers. \
The average score for all the accepted answers. \
The average answer count per question. \
The comment count for each of the 10 answers with the highest score. \
Collect and return the calculated statistics in tabular, HTML or JSON format.

INSTALLATION PROCEDURE \
`python setup.py install`

INPUT EXAMPLE \
`stats --since '2016-06-02 10:00:00' --until '2016-06-02 11:00:00' [--outputformat json(tabular or html)]`

EXECUTION\
`python stats.py --since 'since_date' --until 'until_date' [--output-format output_format --key stack_api_key]`

OUTPUT \
Total accepted answers\
Average score of the accepted answers\
Average answers per question\
Dictionary of top ten answers comment count

TESTING\
`python -m unittest discover -s test`
