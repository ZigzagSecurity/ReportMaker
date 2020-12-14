# Bug report


<br ><br >

**Report by :** zigzag  
[@zigzagCyberSec](https://twitter.com/ZigzagCyberSec)


**Recipient :** Bob  
**Company :** yolo company
<br ><br ><br ><br ><br ><br >
<div class="page"/>

# Findings list

| Number | Host   |     Ports      | findings   |  Links   |
|--------|----------|-------------|-------------|----------|
|    1     | api.yolo.com |  80 | Information disclosure | [Go to finding](#find1)   |
|    2    |         |               |           |  [Go to finding](#find2)   |
|    3    |         |               |           |  [Go to finding](#find3)   |
|    4     |         |               |           |  [Go to finding](#find4)   |
|    5     |         |               |           |  [Go to finding](#find5)   |

<div class="page"/>

# <a name="find1"></a> Finding 1 - Information disclosure
## Summary

An API is accessible without authentication. It is possible to query its endpoints to get information about the company and the clients. This could lead to the compromision of confidential data and help in the the attackers to build a more advance attack.

## Risk breakdown

**Likelihood :** Low / Medium / High  
**Attack Complexity :** Low / Medium / High  
**Risk :** Low / Medium / High

<br >

**Impact metrics :**  
[x] Confidentility  
[ ] Integrity  
[ ] Availibilty  

<br >

**Criticity :** Low / Medium / High

<br >

## Step to reproduce
Here are the step by step walkthrough to reproduce the bug.

```ruby
  def foo
    puts 'bar'
  end
```


~~~ {.text breaklines=true bgcolor=bg fontsize=\footnotesize}
A) Target IP: 192.168.100.1
--------------------------------------

Main Objectives:
- Get shell on machine
- Obtain Account of Domain Controller

B) Target IP: 192.168.100.2
--------------------------------------

Main Objectives:
- Get root shell access to machine
- Dump full Database
~~~


## Impact

Just explain how bad it is !



## Recommendations

Here you have some basics recommendations.
- There a list
- Again some stuff
  - and the end

## References

1. [somewhere](https://)
2. [Somewhere 2](https://)
3. [Somewhere 3](https://)

<div class="page"/>

# <a name="find2"></a>Finding 2 - New finding
## Summary
## Risk breakdown
## Step to reproduce
## Impact
## Recommendations
## References