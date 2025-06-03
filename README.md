# Time-Series-Analysis : Modelisation and prevision of température in Paris

This project analyzes the temperature in Paris. The goal is to model the time series data and generate a forecast.

  📊 Data source
  
    ECA&D（European Climate Assessment & Dataset） 
    Paris, Jan 2015 – Dec 2024 
  
  📈 Analytical Steps and Results:
  
    Seasonal Decomposition 
      -> Clear seasonal pattern observed.
      
    SARIMA Model Application
      Parameters optimized via grid search: p, q, P, D, Q.
      Model fitted and evaluated based on AIC.
      -> SARIMA AIC: 408.5 (ARIMA AIC: 459.1)

    Residual Diagnostics
      -> No periodic structure detected in residuals.
  
  ➡️ Forecast
    
    Forecast for 2025 generated.

=======================================================================================

Modélisation et prévision de température à Paris

Ce projet analyse la température à Paris. L'objectif est de modéliser les données chronologiques et de générer une prévision.

  📊 Data source
  
    ECA&D（European Climate Assessment & Dataset） 
    Paris, Jan 2015 – Déc 2024
  
  📈 Analytical Steps and Results:
  
    Seasonal Decomposition 
      -> Saisonnalité clairement identifiée.
      
    Application du modèle SARIMA -> 
      Optimisation des paramètres par recherche par grille : p, q, P, D, Q.
      Modèle ajusté et évalué selon l'AIC.
      -> SARIMA AIC: 408.5 (ARIMA AIC: 459.1)

    Vérification du bruit blanc
      -> Aucun motif périodique détecté dans les résidus.
  
  ➡️ Forecast
    
    Prédiction de la température pour 2025 réalisée.

=======================================================================================

パリの気温のモデル化と予測

このプロジェクトでは、パリの気温を分析し、時系列データのモデル化と予測を行った。

  📊 データソース
  
    ECA&D（European Climate Assessment & Dataset） 
    パリ, 2015年1月～2024年12月
  
  📈 統計検定と結果:
  
    季節分解
      -> 季節性が明確に確認された。
      
    SARIMAモデルの適用
      グリッドサーチにより、パラメータ p, q, P, D, Q を最適化。
      モデル構築・フィット・評価（AICに基づく）
      -> SARIMA AIC: 408.5 (ARIMA AIC: 459.1)

    ホワイトノイズの確認
      -> 残差に周期性は見られなかった。
  
  ➡️  予測
    
    2025年の気温を予測
