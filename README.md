# [HonKit](https://github.com/HonKit/HonKit) + [gitbook-plugin-uml](https://github.com/vowstar/gitbook-plugin-uml)

Example

```uml
@startuml

	Class Stage
	Class Timeout {
		+constructor:function(cfg)
		+timeout:function(ctx)
		+overdue:function(ctx)
		+stage: Stage
	}
 	Stage <|-- Timeout

@enduml
```

## Usage

    npm run honkit:serve