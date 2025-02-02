<p>
<div align="center">
  <img src="https://img.shields.io/badge/-Python-98b982?style=for-the-badge&logo=python&logoColor=98b982&labelColor=282828">
</div>
</p>

```python
class Person:
  def __init__(self):
    self.__name = 'Nikita'
    self.__username = 'nerma'
    self.__location = 'Republic of Belarus'
    self.__telegram = "https://t.me/eeenn0"
  
  def __str__(self):
    return self.__name

if __name__ == '__main__':
    person: Person = Person()
