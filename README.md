```ex
defmodule AboutMe do
  @greeting "hello, welcome to my profile"

  def greeting, do: @greeting

  def to_string do
    "3rd year software engineering student, interested in full stack and backend web development"
  end

  def currently_learning do
    [
      "rust programming",
      "system design and architecture",
      "latest web-tech trends",
      "building and shipping"
    ]
  end
end
```
