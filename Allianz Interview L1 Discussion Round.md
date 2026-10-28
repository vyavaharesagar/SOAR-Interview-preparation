difference between a list and a tuple in Python?
aws stack
how do you secure the ec2 instance?
how do you connect the aws secret manager?
how do you connect the s3 bucket and store the files?
please explain oops concept by sharing screen and with examples?
what is decorator explian with example?
status codes 201 200 difference? and 429 means?
coding example of creating a list and appending and element
coding example of status codes and return the json. write a function.
tell me about yourself?
if you want to integrate LLM where you will implement it?
what is most challanging task in your career you have faced?
why haven't used the script based your own soar tool instead of n8n?
what is cloudwatch?
what is soar? how you have implemented it?
can u write a fast api code to route a request?


arr = []
arr.append(2)
print(arr)

def check_status(response):
  res = {}
  if response == 200:
    res["200"] = "success"
  if response == 400:
    res["400"] = "Not Found"

  return res

print(check_status(200))

