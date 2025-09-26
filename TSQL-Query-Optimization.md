# TSQL QUERY OPTIMIZATION

## Query Execution Steps

1. VERIFY
  - Is everything written right?
  - Does it has objects? Include intern objects
  - Do we have the permissions?
  - Can I do unions?

2. PREPARE
  - Do I have a previous plan for this query?
  - Query metadata (statistics, indexes, resources)
  - Prepare execution plan
      - Table's order
      - do I have sugesions?

3. EXECUTE
   - Run de query
   - Show teh information, to write a table, etc


## REFERENCES

NAMASDATA course "Optimización de consultas TSQL en SQLServer (https://www.namasdata.com/)
