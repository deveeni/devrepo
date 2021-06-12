1. 자바스크립트 비동기 처리에 대해서
- 비동기란 요청을 보낸 후 응답과 관계없이 다음 동작을 실행할 수 있는 방식이다.
- 자바스크립트는 Single Thread 이다. 그렇기 때문에 이벤트 루프에 기반하여 비동기 처리를 할 수 있다.
- 브라우저에서 제공하는 WebAPIs, Event Table, Callback Queue, EventLoop 등으로 구성 되어있다.
- 즉시 처리 하지 못하는 이벤트들을 WebAPIs를 이용하여 이벤트의 콜백을 콜백큐로 보낸다.
- 이벤트루프를 통해 콜스택이 비었을 경우 실행한다.
- 비동기 처리를 위해 Promise, Async Await 를 사용 할 수 있다.

``Q. How Javascript Asynchronous Works
- Asynchronous is a way in which a request can be sent and then executed regardless of its response.
- JavaScript is a single thread. This allows asynchronous processing based on event loops.
- It consists of Web APIs, Event Table, Callback Queue, EventLoop, and more provided by the browser.
- Events that cannot be processed immediately are sent to a callback of events using Web APIs.
- Run when the callstack is empty through the event loop.
- Promise, Async Await can be used for asynchronous processing.
