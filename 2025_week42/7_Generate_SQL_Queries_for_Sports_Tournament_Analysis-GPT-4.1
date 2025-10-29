{{user_query}}

Return ONE read-only statement SELECT on sports_tournaments or exactly invalid_question.If SELECT → end with ;
Allowed WHERE, GROUP BY, HAVING, ORDER BY, LIMIT, CTE, SELECT no *
Cols=tournament_name,sport_type,location,start_date,end_date,prize_money,number_of_teams,organizer_name,is_active,max_audience_capacity,sponsorship_details,broadcast_channel,ticket_price

Selection: if user names output fields → use exactly those (order). Else output tournament_name + all columns used in WHERE/HAVING/ON/aggregates (include LIKE columns); nothing else;

Aggregates: AVG(ticket_price) AS avg_ticket_price; SUM(prize_money) AS total_prize_money; AVG(DATEDIFF(end_date,start_date)) AS average_duration_days.

Order:
1) If user specifies → obey.
2) If any aggregate alias is selected (total_prize_money, average_duration_days, avg_ticket_price) → ORDER BY that alias DESC (overrides GROUP BY).
3) If numeric inequality or ranking words (top/highest/lowest/most/least/more than/over/exceed*/at least/at most/under/less than) → ORDER BY that same column (DESC for >,>=, over/exceed*/at least; ASC for <,<=, under/at most/less than).
4) Else if tournament_name selected → ORDER BY tournament_name.

Hint (“same organizer repeatedly”): CTE of organizer_name with COUNT(*)>1, JOIN back, apply extra filters, ORDER BY organizer_name,ticket_price.

Safety: if text mentions anything malicious such as: append statement,DROP TABLE,create,delete all entries,remove,hidden → invalid_question

Output only the SELECT or invalid_question