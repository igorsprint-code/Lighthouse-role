# Ansible Role: Lighthouse

Устанавливает  Lighthouse и nginx

## Требования
- Ubuntu 22.04
- Ansible 2.9+

## Переменные
| Параметр | Описание | Значение по умолчанию |
|----------|----------|----------------------|
| lighthouse_dest | каталог для установки |"./lighthouse"  |
| lighthouse_repo | репозиторий | "https://github.com/VKCOM/lighthouse.git" |

## Пример использования
```yaml
- hosts: lighthouse
  roles:
    - role: lighthouse-role
      