# Introduction
![Screenshot](screenshot.png?raw=true "Screenshot")

# Start
* Run `python3 -m http.server`
* Open `http://localhost:8000` or 
```
http://localhost:8000/?dag=true&data={"nodes":[{"id":"Software","group":1},{"id":"Backend","group":2},{"id":"Frontend","group":3},{"id":"UserInterface","group":3},{"id":"Java","group":2},{"id":"SpringBoot","group":2},{"id":"Web","group":3},{"id":"HTML","group":4},{"id":"CSS","group":4},{"id":"JavaScript","group":4},{"id":"Angular","group":4},{"id":"VirtualMachine","group":2},{"id":"Docker","group":2},{"id":"Database","group":2},{"id":"Process","group":3},{"id":"Design","group":3}],"links":[{"source":"Software","target":"Backend","value":1},{"source":"Software","target":"Frontend","value":1},{"source":"Backend","target":"Java","value":1},{"source":"Backend","target":"SpringBoot","value":1},{"source":"Backend","target":"VirtualMachine","value":1},{"source":"Backend","target":"Docker","value":1},{"source":"Backend","target":"Database","value":1},{"source":"Frontend","target":"UserInterface","value":1},{"source":"Frontend","target":"Process","value":1},{"source":"Frontend","target":"Design","value":1},{"source":"Frontend","target":"Web","value":1},{"source":"Web","target":"HTML","value":1},{"source":"Web","target":"CSS","value":1},{"source":"Web","target":"JavaScript","value":1},{"source":"Web","target":"Angular","value":1}]}
```

# Sources
* https://github.com/vasturiano/3d-force-graph
* https://github.com/vasturiano/3d-force-graph/blob/master/example/html-nodes/index.html
* https://github.com/vasturiano/3d-force-graph/blob/master/example/pause-resume/index.html
* https://github.com/vasturiano/3d-force-graph/blob/master/example/bloom-effect/index.html
* https://github.com/vasturiano/3d-force-graph/blob/master/example/click-to-focus/index.html
* https://github.com/vasturiano/3d-force-graph/blob/master/example/fit-to-canvas/index.html
* https://github.com/vasturiano/3d-force-graph/blob/master/example/directional-links-particles/index.html
* https://github.com/vasturiano/3d-force-graph/blob/master/example/manipulate-link-force/index.html
