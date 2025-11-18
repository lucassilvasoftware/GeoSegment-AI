# GeoSegment – Segmentação Semântica de Imagens Aéreas

Este repositório contém o projeto desenvolvido para automatizar a segmentação semântica de imagens aéreas, com foco no mapeamento ambiental e identificação de classes de uso e cobertura da terra.

A ferramenta permite o envio de imagens, processamento via modelo treinado e geração de mapas temáticos de forma simples e reprodutível.

## Demonstração
A interface web pode ser acessada em:
https://geo-segmentation-frontend-production.up.railway.app/

## Principais Componentes
- Modelo de segmentação baseado em DeepLabV3+ (PyTorch)
- API de inferência desenvolvida em FastAPI
- Interface web construída em React
- Containerização com Docker para padronização do ambiente
