# go-webrtc-signaling


webrtc signaling  server



signal  server


peers

```
{
‘user_id’:system
‘type’:’peers’
‘room’:’default’,
‘message’:{‘users’:[]}
}

```


offer

```
{
‘user_id’:xxx,
‘type’:’offer’,
‘room’:’room’
‘message’:
	{
		‘targetUserId’:’’,
		‘eventName’:’offer’,
		
		‘data’:{
			‘offer’:{
				‘type’:’’
				‘sdp’:’’
			}
			'connectionId':str
		}
	}
}

```


answer

```
{
‘user_id’:xxx,
‘type’:’answer’,
‘room’:’room’
‘message’:
	{
		‘targetUserId’:’’,
		‘eventName’:’answer’,
		‘data’:{
			‘answer’:{
				‘type’:’’
				‘sdp’:’’
			},
			'connectionId':str
		}
	}
}

```


ice


```
{
‘user_id’:xxx,
‘type’:’offer’,
‘room’:’room’
‘message’:
	{
		‘targetUserId’:’’,
		‘eventName’:’offer’,
		‘data’:{
			‘iceCandidate’:{
				
			},
			'connectionId':str
		}
	}
}

```





peer_removed

```
{

'user_id':xxx
'type':'peer_removed'
'room':'xxx'
'message':'xxxx'
}

```

peer_connected

```
{

'user_id':xxx
'type':'peer_connected'
'room':'xxx'
'message':'xxxx'
}

```
