# Akaeva Diana

Frontend Developer

## Contact information

* **Email:** cheperish@mail.ru
* **GitHub:** [Encors](https://github.com/Encors)

## Skills

* HTML5, CSS3
* БЭМ (BEM)
* JavaScript
* React
* Webpack
* Git

## Courses

* [Web-разработчик](https://practicum.yandex.ru/profile/web/) — Яндекс Практикум
* [JavaScript Manual](https://learn.javascript.ru/) (in progress)
* [RS Schools Course — JavaScript/Front-end2023Q1](https://app.rs.school/) (in progress)

## English

B1 (according to the online test at EFset Logo www.efset.org)

## Code example

Popup component of one of my projects:

```
export default function InfoTooltip({ onClose, isOpen, responseInfo, classSelector }) {
  return (
    <Popup isOpen={isOpen} classSelector={classSelector} onClose={onClose}>
      <div className="popup__container popup__container-info-tooltip">
        <button className="popup__close-btn button" type="button" />
        <img
          src={responseInfo.status ? register_ok : not_register}
          className="popup__image"
          alt="Иконка статуса регистрации / авторизации"
        />
        <h2 className="popup__title popup__title_type_info-tooltip">
          {responseInfo.text}
        </h2>
      </div>
    </Popup>
  );
}
```
