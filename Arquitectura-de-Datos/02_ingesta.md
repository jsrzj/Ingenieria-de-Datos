# 📥 Capa de Ingesta

## 🎯 Objetivo
Transportar los datos desde las fuentes de origen hacia la plataforma de datos de forma segura, confiable y eficiente.

## ⚙️ Funciones
- Capturar datos desde múltiples fuentes.
- Mover datos en tiempo real o por lotes (batch).
- Gestionar colas de mensajes y eventos.
- Controlar errores y reintentos.
- Garantizar la trazabilidad del flujo de datos.

## 🌐 Open Source
- Apache Kafka
- Apache NiFi
- Airbyte
- Logstash

## 💰 Tecnologías de Pago
- Informatica PowerCenter
- Fivetran
- Talend Data Integration
- Confluent Cloud

## ☁️ Azure / Microsoft
- Azure Data Factory
- Azure Event Hubs
- Azure Service Bus
- Azure Stream Analytics

## 📝 Ejemplo

Una empresa necesita recopilar información de diferentes sistemas:

- PostgreSQL → Datos de clientes.
- Salesforce → Datos comerciales.
- API externa → Tipo de cambio.
- Sensores IoT → Datos en tiempo real.

Apache Kafka o Azure Event Hubs reciben los eventos, mientras que Azure Data Factory mueve los datos hacia el Data Lake para su almacenamiento.

## 🔑 Idea clave

La capa de ingesta es el **puente entre las fuentes de datos y la plataforma analítica**, asegurando que la información llegue correctamente a las siguientes capas.