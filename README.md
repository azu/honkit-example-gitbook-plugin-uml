# [HonKit](https://github.com/HonKit/HonKit) + [gitbook-plugin-uml](https://github.com/vowstar/gitbook-plugin-uml)

Code Block pattern

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

`{% uml %}` pattern

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

`src` File pattern

{% uml src="test.plantuml" %}{% enduml %}

## Usage

    npm run honkit:serve