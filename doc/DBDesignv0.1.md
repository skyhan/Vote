数据库表设计 v0.1版本

tables:

vote:	v_id, type_id, owner(u_id), content, limit, is_closed, close_time, create_time, expect_close_time
vote_type: type_id, type_content
vote_choice:	c_id, v_id, content, count
user:	u_id, username, password, nickname
ballot:	b_id, c_id, u_id, ip, date


vote_review: r_id, v_id, content, date, u_id
主要需要解决投票类型的问题，比如匿名，限定人数等跟随投票类型变化的属性如何分表
不断完善，欢迎补充
