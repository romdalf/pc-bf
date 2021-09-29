```yaml 
apiVersion: v1
kind: Human
metadata:
  name: project-xyz-final
  labels:
    pronouns: he/him/his
    nickname: Rom
    origins: Belgium
spec:
  humain:
    - name: Romuald
      image: pc-bf:1981.07-001
      command: ["/bin/sh"]
      args: ["-c", 'git clone --single-branch --branch matrix-rev-01 https://github.com/rovandep/pc-bf.git; cd battery; ./configure; make; ./run']
      env:
        - name: Country
          value: "Netherlands"
        - name: Town
          value: "Eindhoven"
        - name: Job
          value: "Cloud Solution Architect"
```
