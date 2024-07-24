## InstructLAB

### Init InstructLAB
```ilab init```
```ilab config init```
```ilab model download```

### Clone repo
```git clone https://github.com/sam-andaluri/instructLAB_knowledge_demo.git```

### Install InstructLAB
```python3 -m venv --upgrade-deps venv\nsource venv/bin/activate\npip cache remove llama_cpp_python\npip install instructlab```

### Copy files to a new taxonomy
```mkdir ./taxonomy/knowledge/tech_industry/startup```
```cp qna.yaml ./taxonomy/knowledge/tech_industry/startup```
```cp startup-failures.md ./taxonomy/knowledge/tech_industry/startup```

### Validate new knowledge
```ilab taxonomy diff```

### Generate synthetic data
```ilab data generate```

### Train model
```ilab model train```

### Test model
```ilab model test```
