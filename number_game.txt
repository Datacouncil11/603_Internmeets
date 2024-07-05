def int_filter(*args):
	'''This int_filter function filter out only integer type of data '''
	l = []
	for i in args:
		if type(i) == int:
			l.append(i)
	return l

def my_dir():
	return 'I am inside number_game module and I am My_dir function'



