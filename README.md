# Revival Cell Attendance

Sunday attendance dashboard for Revival Cell, KNUST Obuasi.

Live page: https://1stmarshall.github.io/revival-cell/

- Reads straight from the Revival Cell Supabase database each time it loads, and refreshes every 5 minutes.
- Uses the public (publishable) key, which can only read the read-only `dash_*` views: names, zones, hostels, counts and absence reasons. Member tables, phone numbers, birthdays and emergency contacts are not readable with it.
- Data is entered through the Jotform Member Registration and Sunday Report forms.
