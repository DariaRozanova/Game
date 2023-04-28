# Game
Основное  
Платформа: **ПК**
Технологии: **C# MonoGame**
Язык: **Русский**
Жанры: **2D Платформер**
Длительность игры: -
Главная игровая механика: **Необратимая смерть (PermaDeath)**

## Сюжет
Ресурсы Земли находятся на исходе, поэтому нужно изучить несколько чужих планет, потенциально пригодных для жизни. Ученым требуются несколько образцов с этих планет(горная порода, растение и животное). Главный герой - астронавт, которому необходимо собрать все артефакты в локации, попутно расправляясь с врагами. 

## Игровой мир
В игре присутствует несколько различных локаций, представляющих планеты, каждая из которых имеет своих уникальных противников и элементы головоломки.
Одна планета - один уровень, включающий в себя три подуровня. На третьем подуровне - босс.

## Возможные варианты локаций и противников

На разных планетах разная гравитация. 
### Планета 1
**Противники:**
* существо ближнего боя, кусается если атаковать спереди, среднее количество хп, атака средняя;
* существо дальнего боя, атака которого представляет собой плевок, от которого можно уворачиваться прыжком, малое количество хп, атака сильная;
* босс, который подпрыгивает, исчезая из поля зрения, приземляется в рандомном месте и может задавить игрока, большое количество хп, атака насмерть, в период между прыжками находится в покое и тогда его можно атаковать;

**Особенности:**
* чтобы открыть проход, нужно передвинуть какой-либо объект на кнопку;
* тросы, за которые можно цепляться и ползать;
* скрытые тунели;
* лужи с токсинами, попадая в которые теряешь хп;

### Планета 2. 
**Противники:**
* существо ближнего боя, когда находишься в его поле зрения, ускоряется и атакует, среднее количество хп, атака средняя;
* существо дальнего боя, источает ядовитый газ, который в опреденном радиусе наносит урон(нужно убить как можно быстрее), малое количество хп, атака средняя;
* босс, есть фаза атаки(кидается снарядами в разные стороны с задержкой между атаками) и фаза восстановления хп (когда здоровье падает до определенного уровня, покоится и хилится, чтобы оставовить фазу, нужно ударить со спины);

**Особенности:**
* липкие стены, по которым можно карабкаться;
* аномальные зоны, в которых мир переворачивается на 180 градусов;
* батуты;

## Геймплей
Два больших уровня в игре. 
Главный герой появляется в начале карты (в месте приземления космического корабля), с лазерным мечом, с помощью которого будет сражаться.
В разных локациях карты будут ждать враги, которые охраняют артефакты.
После сбора всех артефактов будет открыт новый уровень.
На карте будут находиться хилки для восстановления хп. 
Таймер. Ограниченное количество времени на карту.
Одна жизнь на карту.
Ниже представлен 1 уровень 1 подуровень (на втором подуровне появятся провники дальнего боя, на третьем добавится босс)

![карта1уровень1подуровень](https://user-images.githubusercontent.com/131370089/233568308-e67f7c0c-e68a-4e14-a0c2-35d4f26cfd36.jpg)
