# govnoedList
- рокси
- камбет
- мяфлик (пес рокси)
- моя мать (шлюха позорная)
- отчим рокси (у него нету матери)
- мегагандон (лон)

# normРебятаList
- двур (мой второй отец)
- я (двур говнокодер)
- лолкана (сеньор по всем языкам)
- отец рокси (норм чел потому что бросил семью рокси)

# code examples
```java
public class govnoedFinderProgram {
  private final List<String> govnoedList = new ArrayList<>();
  
  public void main(String[] args) {
    govnoedList.add("рокси");
    govnoedList.add("камбет");
    govnoedList.add("мяфлик (пес рокси)");
    govnoedList.add("моя мать (шлюха позорная)");
    govnoedList.add("отчим рокси (у него нету матери)");
    govnoedList.add("мегагандон (лон)");
    govnoedList.forEach(this::killFamily);
  }

  private void killFamily(String name) {
    Family family = Family.findByName(name).kill();
  }
}
```

```java
public class normРебятаFinderProgram {
  private final List<String> normРебятаList = new ArrayList<>();
  
  public void main(String[] args) {
    normРебятаList.add("двур (мой второй отец)");
    normРебятаList.add("я (двур говнокодер)");
    normРебятаList.add("лолкана (сеньор по всем языкам)");
    normРебятаList.add("отец рокси (норм чел потому что бросил семью рокси)");
    normРебятаList.forEach(чел -> {
      System.out.println("Норм пацанчик: " + чел)
    });
  }
}
```
