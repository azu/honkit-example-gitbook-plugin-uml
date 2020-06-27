# [HonKit](https://github.com/HonKit/HonKit) + [gitbook-plugin-uml](https://github.com/vowstar/gitbook-plugin-uml)

Code Block

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

`{% uml %}`

{% uml %}
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
{% enduml %}

File

{% uml src="test.plantuml" %}{% enduml %}

## Usage

    npm run honkit:serve