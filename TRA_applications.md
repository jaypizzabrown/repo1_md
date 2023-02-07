
#mermaid diagram

Here is a simple flow chart:

```mermaid
graph TD;
    A-->#1;
    B-->#1;
    X<-->#1;
    C-->#1;
    D-->#1;
    #1-->2;
    #1-->3;
```

Here is a second simple flow chart:

```mermaid
graph TD;
    frontoffice<-->MQ_Backoffice;
    CICS_WS_1<-->frontoffice;
    CICS_WS_2<-->frontoffice;
    Java_WS<-->frontoffice;
    
```
#table

| blabla | bliblibli | bloubloublpou | etpuisquoi | amityville |
| :---: | :---: | :---: | :---: | :---: |
| aaaaa | sdsqdqsdq | dsqdsqdsqdsqd | Oracle  | --- |
| dqdsqdsqddc | sdsdsdsd | nosql | tomcat | jjjjjkkj |



bon sinon tout va bien

...
bon sinon tout va bien :)
...

exemple de code 
`exemple de code` 

sequenceDiagram
    participant Alice
    participant Bob
    participant John
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
