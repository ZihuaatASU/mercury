select event_id, first_reported_link from cu_gsr_event group by first_reported_link order by count(first_reported_link) desc;
